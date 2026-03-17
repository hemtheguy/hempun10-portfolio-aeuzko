---
title: Projects - Hem Bahadur Pun
display: Projects
description: List of projects that I am proud of
wrapperClass: 'text-center'
art: dots
projects:
  Main Projects:
    - name: 'devdaily'
      link: 'https://github.com/hempun10/devdaily'
      desc: 'A TypeScript project with a clean homepage for daily developer insights.'
      icon: 'i-carbon-code'
    - name: 'my_first_react_project'
      link: 'https://github.com/hempun10/my_first_react_project'
      desc: 'A movie application built using React and openmdAPI.'
      icon: 'i-carbon-application-web'
    - name: 'Gitfolio'
      link: 'https://github.com/hempun10/Gitfolio'
      desc: 'A portfolio project using TypeScript for showcasing GitHub profiles.'
      icon: 'i-carbon-folder-open'
  Side Projects:
    - name: 'devdaily-docs'
      link: 'https://github.com/hempun10/devdaily-docs'
      desc: 'Documentation for the devdaily project, written in MDX.'
      icon: 'i-carbon-document'
---

<ListProjects :projects="frontmatter.projects" />