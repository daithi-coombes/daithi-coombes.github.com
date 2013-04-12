---
layout: post
title: "WP Plugin Framework"
description: ""
category: 
tags: [dev]
repo: wp-plugin-framework
---
{% include JB/setup %}

may work, but completely in development


This framework is meant to be light, portable and allow easier use of MVC architecture
than currently. Its end goal is to streamline the production of plugins.

This project will end up splitting into two, one pre php 5.3 and one 5.3 >.
Contributers welcome


Tasks:
 - implement phpunit tests
 - simplify directory structure:
  suggestion:
   - index.php
   - application/
     - class.controller.php
     - class.config.php
   - includes/
     - 3rd.party.js
     - 3rd.party.class.php
   - modules/
     - my.plugin.class.php
     - my.plugin.inc.php
   - public
     - js/plugin.main.js
     - css/plugin.style.css
     - my.view.file.php
     - my.modal.window.php
 - map/group important callbacks, for easier understanding of the code flow
 - review the controller/view relation.