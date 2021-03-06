+++
title = "Create a Cluster"
date = 2018-04-28T12:07:15+02:00
weight = 20
pre = "<b></b>"
+++

## Create a Cluster

{{% notice note %}}
You can try setting up a cluster by yourself using our demo at [cloud.kubermatic.io](https://cloud.kubermatic.io)!
{{% /notice %}}

### Step 1 – Select your Project

Before you can manage clusters or SSH keys, select your current project by using the project list after you logged in or use the dropdown in the top left corner of the page. After choosing the project, the relevant menu items will become active.

![Screenshot of Kubermatic's first cluster creation wizard page](/img/getting_started/manage_projects/projects_02.png)

### Step 2 – Specify the cluster name and Kubernetes version

The cluster name is how you will identify your Kubernetes cluster instance. Choose a name that is easy for you to remember. You must also select your desired Kubernetes version.

![Screenshot of Kubermatic's first cluster creation wizard page](/img/getting_started/create_cluster/kubermatic_00.png)

![Screenshot of Kubermatic's first cluster creation wizard page](/img/getting_started/create_cluster/kubermatic_01.png)

### Step 3 – Choose a cloud provider for your Kubernetes nodes

Choose a cloud provider for your Kubernetes nodes to be deployed by Kubermatic. Your nodes can be placed in any cloud you like.

![Screenshot of Kubermatic's second cluster creation wizard page](/img/getting_started/create_cluster/kubermatic_02.png)

### Step 4 – Select the datacenter of your cloud provider

This is the datacenter of your cloud provider. Your worker nodes will get deployed there.

![Screenshot of Kubermatic's third cluster creation wizard page](/img/getting_started/create_cluster/kubermatic_03.png)

### Step 5 – Enter your provider credentials and configure your worker nodes

Enter your provider specific credentials so that Kubermatic can configure your worker machines and integrate them into your cluster.

{{% notice tip %}}
This step varies depending on the selected provider! You will be asked for different provider credentials when choosing AWS or Google for example
{{% /notice %}}

![Screenshot of Kubermatic's fourth cluster creation wizard page](/img/getting_started/create_cluster/kubermatic_04.png)

### Step 6 – Review your configuration settings and confirm cluster creation

Check wether all your configuration settings are correct and create your cluster!

![Screenshot of Kubermatic's final cluster creation wizard page](/img/getting_started/create_cluster/kubermatic_05.png)

Please note that depending on the capacities in the seed cluster and the chosen cloud provider, cluster creation can take up to a few minutes until your nodes are ready.
