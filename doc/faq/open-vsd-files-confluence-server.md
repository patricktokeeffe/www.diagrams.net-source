---
title: Open .vsd, .vdx and .vss files in draw.io for Confluence Server
layout: page
faq: true
categories: [Confluence Data Center and Server, Import]
---

While ``.vsd``, ``.vdx`` and ``.vss`` import is not supported in Confluence Server, there are a number of ways you can convert these to a .drawio diagram and add them to your instance.

**Convert to a ``.vsdx`` diagram:** Open the diagram file in your normal Microsoft editor, version 2013 or later, and save it as a ``.vsdx`` file. Create a new draw.io diagram in your Confluence Server instance, then drag and drop the .vsdx file into the diagram editor.

**Use draw.io:** Create a new diagram [in our online editor](https://app.diagrams.net), then drag and drop the ``.vsd``, ``.vdx`` or ``.vss`` file onto the drawing canvas. Copy and paste the diagram into a new draw.io diagram in your Confluence Server instance.

**Use the draw.io conversion server:** An administrator can configure your Confluence Server instance to use our [conversion server](https://convert.diagrams.net/VsdConverter/api/converter) to allow users to convert these files transparently.

[See how to configure the draw.io server settings to allow .vsd conversion in Confluence Server using the ``vsdurl`` parameter](/doc/faq/configure-drawio-confluence-server.html)
