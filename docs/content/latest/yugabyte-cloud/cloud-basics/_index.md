---
title: Deploy clusters in Yugabyte Cloud
linkTitle: Deploy clusters
description: Deploy clusters in Yugabyte Cloud.
headcontent: Deploy production-ready clusters.
image: /images/section_icons/index/quick_start.png
section: YUGABYTE CLOUD
menu:
  latest:
    identifier: cloud-basics
    weight: 25
isTocNested: true
showAsideToc: true
---

Using Yugabyte Cloud, you can create single region clusters that can be deployed across multiple and single availability zones.

You deploy clusters in Yugabyte Cloud using the **Create Cluster** wizard.

Before deploying a cluster, you need to decide on the following:

- Cloud provider and regions - Where you deploy the cluster will impact latencies. For a list of currently supported regions in Yugabyte Cloud, refer to [Cloud provider regions](../release-notes/#cloud-provider-regions).
- Cluster size - Size your cluster to the potential load. As Yugabyte Cloud supports both horizontal and vertical scaling, you can always change this later to better match your performance requirements.
- Fault Tolerance - The fault tolerance determines how resilient the cluster is to node and cloud zone failures. You cannot change the fault tolerance after the cluster is created.
- VPC network - Virtual Private Cloud (VPC) peering allows applications running on instances on the same cloud provider as your Yugabyte Cloud cluster to communicate with your cluster without traversing the public internet. If you want your cluster to be in a dedicated VPC and to be peered with an application VPC, you must set up the VPC _before_ you create your cluster.

<div class="row">

  <div class="col-12 col-md-6 col-lg-12 col-xl-6">
    <a class="section-link icon-offset" href="create-clusters-overview/">
      <div class="head">
        <img class="icon" src="/images/section_icons/introduction/benefits.png" aria-hidden="true" />
        <div class="title">Plan your cluster</div>
      </div>
      <div class="body">
        Plan your production deployment.
      </div>
    </a>
  </div>

  <div class="col-12 col-md-6 col-lg-12 col-xl-6">
    <a class="section-link icon-offset" href="cloud-vpcs/">
      <div class="head">
        <img class="icon" src="/images/section_icons/manage/backup.png" aria-hidden="true" />
        <div class="title">VPC networks</div>
      </div>
      <div class="body">
        VPC networking in Yugabyte Cloud.
      </div>
    </a>
  </div>

  <div class="col-12 col-md-6 col-lg-12 col-xl-6">
    <a class="section-link icon-offset" href="create-clusters-free/">
      <div class="head">
        <img class="icon" src="/images/section_icons/quick_start/create_cluster.png" aria-hidden="true" />
        <div class="title">Create a free cluster</div>
      </div>
      <div class="body">
        Create a free cluster in Yugabyte Cloud.
      </div>
    </a>
  </div>

  <div class="col-12 col-md-6 col-lg-12 col-xl-6">
    <a class="section-link icon-offset" href="create-clusters/">
      <div class="head">
        <img class="icon" src="/images/section_icons/quick_start/create_cluster.png" aria-hidden="true" />
        <div class="title">Create a standard cluster</div>
      </div>
      <div class="body">
        Create a new standard cluster in Yugabyte Cloud.
      </div>
    </a>
  </div>

</div>
