---
title: SL2100
tags: [getting_started]
keywords: release notes, announcements, what's new, new features
last_updated: July 16, 2016

sidebar: mydoc_sidebar
permalink: mydoc_release_notes_60.html
folder: mydoc
---
## ACCEDER A LA PLANTA
Para ingresar a las configuraciones de la planta debe utilizar un browser y colocar la IP 172.16.0.10 donde se le pedirá ingresar las siguientes credenciales:

Usuario:tech
Password:12345678

## EXTENSIONES




## LINEAS

You can creates folders and subfolders for your pages, similar to how you can store posts in folders and subfolders. When Jekyll builds the site, all pages get pushed into the root directory as single html files (rather than being pushed inside folders, or remaining in subfolders). See [Pages][mydoc_pages] for more details.

## SISTEMA

You can use include templates for notes, tips, and warnings. These include templates make it easier to insert notes. If you make an error, you're immediately made aware since the site won't build. See [Alerts][mydoc_alerts] for more details.

## Image templates

Similar to alerts, images also have include templates. You can insert both regular images and inline images, such as images that are a button or icon. See [Images][mydoc_images] for more details.

## Automated links using Markdown formatting

Instead of using YAML references to handle links, I've switched to a Markdown reference style approach. A links.html file iterates through the sidebar files and formats the content in the Markdown reference. You then just use Markdown syntax for the links. See [Links][mydoc_hyperlinks] for more details.

## Workflow maps

If you want to display a workflow map for a process, you can do so by adding some properties in your frontmatter. The workflow map helps guide users through a process. Both simple and complex workflow maps are available. For more details, see [Workflow maps][mydoc_workflow_maps].
