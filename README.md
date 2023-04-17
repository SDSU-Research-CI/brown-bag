# 👋 Welcome to the Instructional Cluster Intro
This repository is designed to be an interactive introduction to the [Instructional Cluster](https://sdsu-research-ci.github.io/instructionalcluster) at San Diego State University.

This intro assumes that you are familiar with a [Linux Operating System](https://en.wikipedia.org/wiki/Linux) and have some level of comfort with commandline interfaces.

## ✔ Mission Objectives
After completing this introduction, you should:
1. Be able to use basic git commands
2. Understand core concepts of containers
3. Be able to use Jupyter Notebooks

## 🔑 Accessing the Instructional Cluster
If you are following this introduction as part of a training offered by [Research and Cyberinfrastructure](https://it.sdsu.edu/research) chances are that you already have access to the Instructional Cluster.

You can check your access to the Instructional Cluster by following these [login instructions](https://sdsu-research-ci.github.io/instructionalcluster/students/loggingin).

If you are greeted by a screen similar to the following, then you have access!

![access](./images/access1.png)

If you don't have access and you are either SDSU Faculty or Staff, then you can submit [this form](https://sdsu.service-now.com/sp?id=sc_cat_item&sys_id=c4ce9d52db0e68509804f271399619a4&sysparm_category=29ac153fdbbf4c9024094672399619e9) to request access. Students will be granted access based on enrollment in courses that are using the Instructional Cluster.

## 👨‍🚀👩‍🚀 Prepare for Launch!
Now that we're cleared for take-off, let's [fire up your Jupyter Noteboook](https://sdsu-research-ci.github.io/instructionalcluster/students/launchcontainer) on the Instructional Cluster. For this introduction we will use the following selections for the given options:

Option    | Selection
:---------|:---------:
GPUs      | 0
CPU Cores | 1
Memory GB | 4
Image     | Stack Datascience

Once you've completed those options click Start. You will then see a screen similar to that below with a progress bar which may take a minute or two to complete. You can click the event log to see what is happening, which we will explain in more detail later in this introduction.

![notebook progress bar](./images/get-started1.png)

After that screen you will see one similar to that below which is your Jupyter Notebook in the Jupyter Lab UI.

![jupyter notebook](./images/get-started2.png)

Next, let's get a copy of this repository and its example notebooks copied into your Jupyter Notebook environment. Click the terminal icon to launch a linux terminal and then enter this command:

```bash
$ git clone https://github.com/SDSU-Research-CI/ic-intro.git
```

You should see output similar to the following, and you should also see a directory "ic-intro" in the file explorer pane:

![cloning ic-intro repository](./images/get-started3.png)

You can also open this readme in your Jupyter Notebook from the file explorer pane by clicking into the ic-intro directory, then right-click README.md > Open with > Markdown preview.

![preview readme](./images/get-started4.png)

## 🚀 Next Destination: Jupyter Notebooks
With our Jupyter Notebook fired up and a copy of this repo cloned, let's launch over to our first topic: [Jupyter Notebooks](./notebooks/jupyter.ipynb).