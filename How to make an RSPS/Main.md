# How to host an RSPS
RSPS (RuneScape Private Server) is the emulation of RuneScape as a third party. It consists of a (modified) client written by JaGeX in Java and a server that controls that client, created by the RSPS community, mostly also written in Java.

There are many different servers out there that all have their own way of doing things and you will encounter a plethora of bugs and missing features as you get familiar with the scene.

In this tutorial we will go over the process of setting up all the things necessary to play your self-hosted version of RuneScape. We'll be using one of the popular revisions in this tutorial so that you may find a lot of extra information about this source online.


## 1. Selecting a revision
Before you can start downloading a "source" (this term is used when referring to a server) you must first decide which revision you want to host.

Revisions are the release numbers JaGeX has been using for years. A list of revisions can be found [here](https://runescape.fandom.com/wiki/Build_number).

Furthermore the RSPS community makes the distinction between the following eras:
* OSRS (All revisions related to Oldschool RuneScape)
* RS2 (+- 317 up to 742)
* EoC (743-766)
* RS3 (773+)
* NXT (this is RS3 with the new client)

Each era has popular revisions that are recommended for new members as there is a lot of information around the released sources for these revisions.

## 2. Finding a source
Searching for a source can sometimes be tricky, especially if you are going for a revision that is uncommon. Many links are outdated and no longer work. Sometimes asking for a download link on an RSPS forum can work. Searching on google using the terms "rsps XXX download" will usually yield good results. You may have to scroll through a few pages on the page before you get the download link (if it was reuploaded).

For our tutorial we're using TODO: PICK DOWNLOAD

## 3. Choosing a development environment
When hosting an RSPS server, you'll need a set of tools to modify and create new content for the server.

### 3.1 JDK
When you program in Java, you need a JDK (Java Development Kit) which is a bundle of tools that enable you to compile Java. Most servers were built before Java 8, especially the clients were built before that. Luckily most of them work fine on Java 8, which is at the time of writing still supported so we'll be using that.

Navigate to [AdoptOpenJDK](https://adoptopenjdk.net/?variant=openjdk8&jvmVariant=hotspot) and download the latest JDK 8 (Hotspot) release for your operating system. Installation instructions can be found on the AdoptOpenJDK website. For Windows it's as simple as running the setup wizard and you're set.

IntelliJ can download JDKs for you from within its UI. We'll get more into IntelliJ in the IntelliJ specific part of this tutorial.

### 3.2 IDE
There are two popular choices often used in the RSPS scene that we will treat in this tutorial:
1. [IntelliJ IDEA](): A refined IDE that has a free and paid version
2. [Eclipse](): A slightly less refined IDE that is free

Click on one to see the IDE specific part of this tutorial.