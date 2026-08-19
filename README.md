# Awesome Robotic Tooling with stars

**A curated list of tooling for professional robotic development in C++ and Python with a touch of ROS, autonomous driving and aerospace**

> To stop reinventing the wheel you need to know about the wheel. This list is an attempt to show the variety of open and free tools in software and hardware development, which are useful in professional robotic development.

Your contribution is necessary to keep this list alive, increase the quality and to expand it. You can read more about it's origin and how you can participate in the [contribution guide](CONTRIBUTING.md) and related [blog post](https://rosindustrial.org/news/2020/5/11/guest-article-on-the-story-of-the-autonomous-logistics). All new project entries will have a tweet from [protontypes](https://twitter.com/protontypes).

<!--lint ignore double-link-->

[<img src="https://i.imgur.com/qI1Jfyl.gif" align="right" width="60%" />](https://github.com/leggedrobotics/xpp) ⭐ 338 | 🐛 8 | 🌐 C++ | 📅 2021-12-09

<!--lint ignore double-link-->

[![](https://img.shields.io/twitter/follow/protontypes?style=social)](https://twitter.com/intent/follow?screen_name=protontypes) [![Join the chat at https://gitter.im/protontypes/community](https://badges.gitter.im/protontypes/community.svg)](https://gitter.im/protontypes/community?utm_source=badge\&utm_medium=badge\&utm_campaign=pr-badge\&utm_content=badge)

<!--toc-->

## Contents

* [Communication and Coordination](#communication-and-coordination)
* [Documentation and Presentation](#documentation-and-presentation)
* [Requirements and Safety](#requirements-and-safety)
* [Architecture and Design](#architecture-and-design)
* [Frameworks and Stacks](#frameworks-and-stacks)
* [Development Environment](#development-environment)
  * [Code and Run](#code-and-run)
  * [Template](#template)
  * [Build and Deploy](#build-and-deploy)
  * [Unit and Integration Test](#unit-and-integration-test)
  * [Lint and Format](#lint-and-format)
  * [Debugging and Tracing](#debugging-and-tracing)
  * [Version Control](#version-control)
* [Simulation](#simulation)
* [Electronics and Mechanics](#electronics-and-mechanics)
* [Sensor Processing](#sensor-processing)
  * [Calibration and Transformation](#calibration-and-transformation)
  * [Perception Pipeline](#perception-pipeline)
  * [Machine Learning](#machine-learning)
  * [Parallel Processing](#parallel-processing)
  * [Image Processing](#image-processing)
  * [Radar Processing](#radar-processing)
  * [Lidar and Point Cloud Processing](#lidar-and-point-cloud-processing)
* [Localization and State Estimation](#localization-and-state-estimation)
* [Simultaneous Localization and Mapping](#simultaneous-localization-and-mapping)
  * [Lidar](#lidar)
  * [Visual](#visual)
  * [Vector Map](#vector-map)
* [Prediction](#prediction)
* [Behavior and Decision](#behavior-and-decision)
* [Planning and Control](#planning-and-control)
* [User Interaction](#user-interaction)
  * [Graphical User Interface](#graphical-user-interface)
  * [Acoustic User Interface](#acoustic-user-interface)
  * [Command Line Interface](#command-line-interface)
* [Data Visualization and Mission Control](#data-visualization-and-mission-control)
  * [Annotation](#annotation)
  * [Point Cloud](#point-cloud)
  * [RViz](#rviz)
* [Operation System](#operation-system)
  * [Monitoring](#monitoring)
  * [Database and Record](#database-and-record)
  * [Network Distributed File System](#network-distributed-file-system)
  * [Server Infrastructure and High Performance Computing](#server-infrastructure-and-high-performance-computing)
  * [Embedded Operation System](#embedded-operation-system)
  * [Real-Time Kernel](#real-time-kernel)
* [Network and Middleware](#network-and-middleware)
  * [Ethernet and Wireless Networking](#ethernet-and-wireless-networking)
  * [Controller Area Network](#controller-area-network)
  * [Sensor and Acuator Interfaces](#sensor-and-acuator-interfaces)
* [Security](#security)
* [Datasets](#datasets)

<!--toc_end-->

## Communication and Coordination

* [Gogs](https://github.com/gogs/gogs) ⭐ 47,740 | 🐛 1,010 | 🌐 Go | 📅 2026-08-06 - Build a simple, stable and extensible self-hosted Git service that can be setup in the most painless way.
* [discourse](https://github.com/discourse/discourse) ⭐ 47,674 | 🐛 255 | 🌐 Ruby | 📅 2026-08-19 - A platform for community discussion. Free, open, simple.
* [mattermost](https://github.com/mattermost/mattermost-server) ⭐ 38,840 | 🐛 966 | 🌐 TypeScript | 📅 2026-08-19 - An open source, private cloud, Slack-alternative.
* [jitsi-meet](https://github.com/jitsi/jitsi-meet) ⭐ 29,769 | 🐛 148 | 🌐 TypeScript | 📅 2026-08-19 - Secure, Simple and Scalable Video Conferences that you use as a standalone app or embed in your web application.
* [Gitflow](https://github.com/nvie/gitflow) ⚠️ Archived - Makes parallel development very easy, by isolating new development from finished work.
* [Wekan](https://github.com/wekan/wekan) ⭐ 21,058 | 🐛 335 | 🌐 JavaScript | 📅 2026-08-19 - Meteor based Kanban Board.
* [openproject](https://github.com/opf/openproject) ⭐ 15,888 | 🐛 227 | 🌐 Ruby | 📅 2026-08-19 - The leading open source project management software.
* [leantime](https://github.com/Leantime/leantime) ⭐ 11,391 | 🐛 314 | 🌐 PHP | 📅 2026-08-15 - Leantime is a lean project management system for innovators.
* [Kanboard](https://github.com/kanboard/kanboard) ⭐ 9,805 | 🐛 168 | 🌐 PHP | 📅 2026-08-11 - Minimalistic Kanban Board.
* [Gitlab](https://github.com/sameersbn/docker-gitlab) ⭐ 8,101 | 🐛 575 | 🌐 Shell | 📅 2026-08-18 - Simple Selfhosted Gitlab Server with Docker.
* [ONLYOFFICE](https://github.com/ONLYOFFICE/CommunityServer) ⭐ 3,155 | 🐛 206 | 🌐 C# | 📅 2026-05-05 -  A free open source collaborative system developed to manage documents, projects, customer relationship and email correspondence, all in one place.
* [Helpy](https://github.com/helpyio/helpy) ⭐ 2,472 | 🐛 230 | 🌐 Ruby | 📅 2023-03-08 - A modern, open source helpdesk customer support application.
* [JIRA API](https://github.com/pycontribs/jira) ⭐ 2,128 | 🐛 236 | 🌐 Python | 📅 2026-08-17 - Python Library for REST API of Jira.
* [Chronos-Timetracker](https://github.com/web-pal/chronos-timetracker) ⭐ 302 | 🐛 76 | 🌐 JavaScript | 📅 2025-10-09 - Desktop client for JIRA. Track time, upload worklogs without a hassle.
* [Taiga](https://github.com/benhutchins/docker-taiga) ⚠️ Archived - Agile Projectmanagment Tool.
* [Taiga API](https://github.com/nephila/python-taiga) ⭐ 138 | 🐛 16 | 🌐 Python | 📅 2026-08-19 - Python Library for REST API of Taiga.
* [DeepL](https://github.com/uinput/deeplator) ⚠️ Archived - An online translator that outperforms Google, Microsoft and Facebook.
* [Agile Development](https://agilemanifesto.org/) - Manifesto for Agile Software Development.
* [kanban](https://gitlab.com/leanlabsio/kanban) - Free, open source, self-hosted, Kanban board for GitLab issues.
* [Grge](https://gitlab.com/ApexAI/grge) - Grge is a daemon and command line utility augmenting GitLab.
* [gitlab-triage](https://gitlab.com/gitlab-org/gitlab-triage) - Gitlab's issues and merge requests triage, automated.
* [Gerrit](https://gerrit.googlesource.com/gerrit/) - A code review and project management tool for Git based projects.
* [gitter](https://gitlab.com/gitlab-org/gitter/webapp) - Gitter is a chat and networking platform that helps to manage, grow and connect communities through messaging, content and discovery.

## Documentation and Presentation

* [Excalidraw](https://github.com/excalidraw/excalidraw) ⭐ 130,005 | 🐛 3,334 | 🌐 TypeScript | 📅 2026-08-16 - Virtual whiteboard for sketching hand-drawn like diagrams.
* [tesseract](https://github.com/tesseract-ocr/tesseract) ⭐ 75,988 | 🐛 485 | 🌐 C++ | 📅 2026-08-17 - Open Source OCR Engine.
* [Pandoc](https://github.com/jgm/pandoc) ⭐ 45,938 | 🐛 1,050 | 🌐 Haskell | 📅 2026-08-18 - Universal markup converter.
* [carbon](https://github.com/carbon-app/carbon) ⭐ 36,089 | 🐛 84 | 🌐 JavaScript | 📅 2026-02-10 - Share beautiful images of your source code.
* [OCRmyPDF](https://github.com/jbarlow83/OCRmyPDF) ⭐ 34,497 | 🐛 98 | 🌐 Python | 📅 2026-08-18 - Adds an OCR text layer to scanned PDF files, allowing them to be searched.
* [PlotNeuralNet](https://github.com/HarisIqbal88/PlotNeuralNet) ⭐ 24,951 | 🐛 89 | 🌐 TeX | 📅 2023-08-21 - Latex code for drawing neural networks for reports and presentation.
* [mkdocs](https://github.com/mkdocs/mkdocs/) ⭐ 22,359 | 🐛 185 | 🌐 Python | 📅 2025-10-20 - A fast, simple and downright gorgeous static site generator that's geared towards building project documentation.
* [overleaf](https://github.com/overleaf/overleaf) ⭐ 18,036 | 🐛 166 | 🌐 JavaScript | 📅 2026-07-10 - An open-source online real-time collaborative LaTeX editor.
* [asciinema](https://github.com/asciinema/asciinema) ⭐ 17,700 | 🐛 8 | 🌐 Rust | 📅 2026-08-14 - Lets you easily record terminal sessions and replay them in a terminal as well as in a web browser.
* [foam](https://github.com/foambubble/foam) ⭐ 17,363 | 🐛 29 | 🌐 TypeScript | 📅 2026-08-13 - Foam is a personal knowledge management and sharing system inspired by Roam Research, built on Visual Studio Code and GitHub.
* [Zotero](https://github.com/zotero/zotero) ⭐ 15,002 | 🐛 1,595 | 🌐 JavaScript | 📅 2026-08-19 - A free, easy-to-use tool to help you collect, organize, cite, and share your research sources.
* [gollum](https://github.com/gollum/gollum) ⭐ 14,312 | 🐛 91 | 🌐 Ruby | 📅 2025-11-24 - A simple, Git-powered wiki with a sweet API and local frontend.
* [ReLaXed](https://github.com/RelaxedJS/ReLaXed) ⭐ 11,797 | 🐛 52 | 🌐 JavaScript | 📅 2025-09-07 - Allows complex PDF layouts to be defined with CSS and JavaScript, while writing the content in a friendly, minimal syntax close to Markdown or LaTeX.
* [Sphinx](https://github.com/sphinx-doc/sphinx/) ⭐ 7,980 | 🐛 1,454 | 🌐 Python | 📅 2026-08-16 - A tool that makes it easy to create intelligent and beautiful documentation for Python projects.
* [paperless](https://github.com/the-paperless-project/paperless) ⚠️ Archived - Index and archive all of your scanned paper documents.
* [github-changelog-generator](https://github.com/github-changelog-generator/github-changelog-generator) ⭐ 7,536 | 🐛 129 | 🌐 Ruby | 📅 2026-03-18 - Automatically generate change log from your tags, issues, labels and pull requests on GitHub.
* [CodiMD](https://github.com/codimd/server) ⭐ 7,373 | 🐛 270 | 🌐 TypeScript | 📅 2026-08-18 - Open Source Online Real-time collaborate on team documentation in markdown.
* [buku](https://github.com/jarun/buku) ⭐ 7,177 | 🐛 6 | 🌐 Python | 📅 2026-08-16 - Browser-independent bookmark manager.
* [Doxygen](https://github.com/doxygen/doxygen) ⭐ 6,551 | 🐛 1,856 | 🌐 C++ | 📅 2026-08-18 - Doxygen is the de facto standard tool for generating documentation from annotated C++ sources.
* [papermill](https://github.com/nteract/papermill) ⭐ 6,470 | 🐛 196 | 🌐 Python | 📅 2026-07-06 - A tool for parameterizing, executing, and analyzing Jupyter Notebooks.
* [Markor](https://github.com/gsantner/markor) ⭐ 5,991 | 🐛 186 | 🌐 Java | 📅 2026-08-05 - A Simple Markdown Editor for your Android Device.
* [jupyter-book](https://github.com/executablebooks/jupyter-book) ⭐ 4,269 | 🐛 667 | 🌐 TypeScript | 📅 2026-08-08 - Build interactive, publication-quality documents from Jupyter Notebooks.
* [patat](https://github.com/jaspervdj/patat) ⭐ 2,741 | 🐛 23 | 🌐 Haskell | 📅 2026-06-25 - Terminal-based presentations using Pandoc.
* [InvoiceNet](https://github.com/naiveHobo/InvoiceNet) ⭐ 2,695 | 🐛 72 | 🌐 Python | 📅 2024-05-03 - Deep neural network to extract intelligent information from invoice documents.
* [landslide](https://github.com/adamzap/landslide) ⭐ 2,094 | 🐛 40 | 🌐 CSS | 📅 2024-01-01 - Generate HTML5 slideshows from markdown, ReST, or textile.
* [Word-to-Markdown](https://github.com/benbalter/word-to-markdown) ⭐ 1,550 | 🐛 13 | 🌐 Ruby | 📅 2026-07-30 - A ruby gem to liberate content from Microsoft Word document.
* [jupyter2slides](https://github.com/datitran/jupyter2slides) ⭐ 792 | 🐛 12 | 🌐 HTML | 📅 2019-09-03 - Cloud Native Presentation Slides with Jupyter Notebook + Reveal.js.
* [Reveal-Hugo](https://github.com/dzello/reveal-hugo) ⭐ 744 | 🐛 45 | 🌐 JavaScript | 📅 2026-05-19 - A Hugo theme for Reveal.js that makes authoring and customization a breeze. With it, you can turn any properly-formatted Hugo content into a HTML presentation.
* [Yaspeller](https://github.com/hcodes/yaspeller) ⚠️ Archived - Command line tool for spell checking.
* [docsy](https://github.com/google/docsy-example) ⭐ 558 | 🐛 16 | 🌐 JavaScript | 📅 2026-07-30 - An example documentation site using the Docsy Hugo theme.
* [libreoffice-impress-templates](https://github.com/dohliam/libreoffice-impress-templates) ⭐ 405 | 🐛 8 | 🌐 Ruby | 📅 2020-02-15 - Freely-licensed LibreOffice Impress templates.
* [Hugo-Webslides](https://github.com/RCJacH/hugo-webslides) ⭐ 133 | 🐛 4 | 🌐 CSS | 📅 2022-02-23 - This is a Hugo template to create WebSlides presentation using markdown.
* [GitLab-Release-Note-Generator](https://github.com/jk1z/GitLab-Release-Note-Generator) ⭐ 100 | 🐛 18 | 🌐 JavaScript | 📅 2023-02-12 - A Gitlab release note generator that generates release note on latest tag.
* [Typora](https://typora.io/) - A Minimalist Markdown Editor.
* [ReadtheDocs](https://docs.readthedocs.io/en/stable/development/buildenvironments.html) - Build your local ReadtheDocs Server.
* [undraw](https://undraw.co/illustrations) - Free Professional business SVGs easy to customize.
* [inkscape](https://inkscape.org/) - Inkscape is a professional vector graphics editor for Linux, Windows and macOS.
* [actions-hugo](https://github.com/peaceiris/) - Deploy website based on Hugo to GitHub Pages.
* [opensourcedesign](https://opensourcedesign.net/resources/) - Community and Resources for Free Design and Logo Creation.
* [olive](https://www.olivevideoeditor.org/) - A free non-linear video editor aiming to provide a fully-featured alternative to high-end professional video editing software.
* [swiftlatex](https://www.swiftlatex.com/) - A WYSIWYG Browser-based LaTeX Editor.
* [SVGrepo](https://www.svgrepo.com/) - Download free SVG Vectors for commercial use.
* [GanttLab](https://gitlab.com/ganttlab/ganttlab) - The easy to use, fully functional Gantt chart for GitLab and GitHub.

## Requirements and Safety

* [awesome-safety-critical](https://github.com/stanislaw/awesome-safety-critical) ⭐ 1,594 | 🐛 0 | 🌐 Python | 📅 2025-03-11 - List of resources about programming practices for writing safety-critical software.
* [fossology](https://github.com/fossology/fossology) ⭐ 1,017 | 🐛 296 | 🌐 HTML | 📅 2026-08-19 - A toolkit you can run license, copyright and export control scans from the command line.
* [doorstop](https://github.com/doorstop-dev/doorstop) ⭐ 657 | 🐛 56 | 🌐 Python | 📅 2026-08-15 - Requirements management using version control.
* [safe\_numerics](https://github.com/boostorg/safe_numerics) ⭐ 222 | 🐛 37 | 🌐 C++ | 📅 2026-08-12 - Replacements to standard numeric types which throw exceptions on errors.
* [open-autonomous-safety](https://github.com/voyage/open-autonomous-safety) ⭐ 180 | 🐛 4 | 🌐 JavaScript | 📅 2018-06-04 - OAS is a fully open-source library of Voyage's safety processes and testing procedures, designed to supplement existing safety programs at self-driving car startups across the world.
* [CarND-Functional-Safety-Project](https://github.com/udacity/CarND-Functional-Safety-Project) ⭐ 90 | 🐛 0 | 📅 2022-07-06 - Create functional safety documents in this Udacity project.
* [ScenarioArchitect](https://github.com/TUMFTM/ScenarioArchitect) ⭐ 36 | 🐛 3 | 🌐 Python | 📅 2024-06-17 - The Scenario Architect is a basic python tool to generate, import and export short scene snapshots.
* [Automated Valet Parking Safety Documents](https://avp-project.uk/publication-of-safety-documents) - Created to support the safe testing of the Automated Valet Parking function using the StreetDrone test vehicle in a car park.
* [Air Vehicle C++ development coding standards](http://www.stroustrup.com/JSF-AV-rules.pdf) - Provide direction and guidance to C++ programmers that will enable them to employ good programming style and proven programming practices leading to safe, reliable, testable, and maintainable code.
* [AUTOSAR Coding Standard](https://www.autosar.org/fileadmin/user_upload/standards/adaptive/17-10/AUTOSAR_RS_CPP14Guidelines.pdf) - Guidelines for the use of the C++14 language in critical and safety-related system.
* [The W-Model and Lean Scaled Agility for Engineering](https://assets.vector.com/cms/content/consulting/publications/AgileSystemsEngineering_Vector_Ford.pdf) - Ford applied an agile V-Model method from Vector that can be used in safety related project management.
* [capella](https://www.eclipse.org/capella/) - Comprehensive, extensible and field-proven MBSE tool and method
  to successfully design systems architecture.
* [robmosys](https://robmosys.eu/) - RobMoSys envisions an integrated approach built on top of the current code-centric robotic platforms, by applying model-driven methods and tools.
* [Papyrus for Robotics](https://www.eclipse.org/papyrus/components/robotics/) - A graphical editing tool for robotic applications that complies with the RobMoSys approach.

## Architecture and Design

* [Architecture\_Decision\_Record](https://github.com/joelparkerhenderson/architecture_decision_record) ⭐ 16,687 | 🐛 10 | 📅 2026-08-12 - A document that captures an important architectural decision made along with its context and consequences.
* [vscode-drawio](https://github.com/hediet/vscode-drawio) ⭐ 9,480 | 🐛 178 | 🌐 TypeScript | 📅 2026-08-07 - This extension integrates Draw\.io into VS Code.
* [Plantuml](https://github.com/plantuml/plantuml-server) ⭐ 2,214 | 🐛 76 | 🌐 Java | 📅 2026-08-07 - Web application to generate UML diagrams on-the-fly in your live documentation.
* [pydeps](https://github.com/thebjorn/pydeps) ⭐ 2,105 | 🐛 47 | 🌐 Python | 📅 2026-08-17 - Python Module Dependency graphs.
* [cpp-dependencies](https://github.com/tomtom-international/cpp-dependencies) ⭐ 781 | 🐛 13 | 🌐 C++ | 📅 2026-01-13 - Tool to check C++ #include dependencies (dependency graphs created in .dot format).
* [Guidelines](https://github.com/S2-group/icse-seip-2020-replication-package/blob/master/ICSE_SEIP_2020.pdf) ⭐ 103 | 🐛 0 | 🌐 Python | 📅 2025-08-07 - How to architect ROS-based systems.
* [aztarna](https://github.com/aliasrobotics/aztarna) ⚠️ Archived -  A footprinting tool for robots.
* [yed\_py](https://github.com/true-grue/yed_py) ⭐ 59 | 🐛 0 | 🌐 Python | 📅 2026-03-21 - Generates graphML that can be opened in yEd.
* [rqt\_launchtree](https://github.com/pschillinger/rqt_launchtree) ⭐ 53 | 🐛 13 | 🌐 Python | 📅 2022-06-08 - An RQT plugin for hierarchical launchfile configuration introspection.
* [yEd](https://www.yworks.com/products/yed) - A powerful desktop application that can be used to quickly and effectively generate high-quality diagrams.
* [rqt\_graph](https://wiki.ros.org/rqt_graph) - Provides a GUI plugin for visualizing the ROS computation graph.
* [draw.io](https://www.draw.io/) - A free online diagram software for making flowcharts, process diagrams, org charts, UML, ER and network diagrams.

## Frameworks and Stacks

* [OpenPilot](https://github.com/commaai/openpilot) ⭐ 63,450 | 🐛 122 | 🌐 Python | 📅 2026-08-19 - Open Source Adaptive Cruise Control (ACC) and Lane Keeping Assist System (LKAS).
* [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/) ⭐ 30,323 | 🐛 50 | 🌐 Python | 📅 2026-08-17 - This is a Python code collection of robotics algorithms, especially for autonomous navigation.
* [Apollo](https://github.com/ApolloAuto/apollo) ⭐ 26,797 | 🐛 1,045 | 🌐 C++ | 📅 2026-04-16 - High performance, flexible architecture which accelerates the development, testing, and deployment of Autonomous Vehicles.
* [ArduPilot](https://github.com/ArduPilot/ardupilot) ⭐ 15,709 | 🐛 3,148 | 🌐 C++ | 📅 2026-08-19 - Open source control software for autonomous vehicles - copters/planes/rovers/boats/submersibles.
* [PX4](https://github.com/PX4/Firmware) ⭐ 12,449 | 🐛 339 | 🌐 C++ | 📅 2026-08-19 - An open source flight control software for drones and other unmanned vehicles.
* [F Prime](https://github.com/nasa/fprime) ⭐ 11,674 | 🐛 432 | 🌐 C++ | 📅 2026-08-19 - A component-driven framework that enables rapid development and deployment of spaceflight and other embedded software applications.
* [open-source-rover](https://github.com/nasa-jpl/open-source-rover) ⭐ 9,587 | 🐛 18 | 🌐 Prolog | 📅 2026-08-13 - A build-it-yourself, 6-wheel rover based on the rovers on Mars from JPL.
* [awesome-ros2](https://github.com/fkromer/awesome-ros2) ⚠️ Archived - A curated list of awesome Robot Operating System Version 2.0 (ROS 2) resources and libraries.
* [astrobee](https://github.com/nasa/astrobee) ⭐ 1,396 | 🐛 31 | 🌐 C++ | 📅 2025-12-02 - Astrobee is a free-flying robot designed to operate as a payload inside the International Space Station (ISS).
* [makani](https://github.com/google/makani) ⚠️ Archived - Contains the working Makani flight simulator, controller (autopilot), visualizer, and command center flight monitoring tools.
* [clover](https://github.com/CopterExpress/clover) ⭐ 681 | 🐛 14 | 🌐 C++ | 📅 2026-04-14 - ROS-based framework and RPi image to control PX4-powered drones.
* [JdeRobot Academy](https://github.com/JdeRobot/RoboticsAcademy) ⭐ 489 | 🐛 59 | 🌐 Python | 📅 2026-08-16 - JdeRobot Academy is an open source collection of exercises to learn robotics in a practical way.
* [CARMAPlatform](https://github.com/usdot-fhwa-stol/CARMAPlatform) ⭐ 436 | 🐛 270 | 🌐 C++ | 📅 2026-08-18 - Enables cooperative automated driving plug-in.
* [pybotics](https://github.com/engnadeau/pybotics) ⚠️ Archived -  An open-source and peer-reviewed Python toolbox for robot kinematics and calibration.
* [mod\_vehicle\_dynamics\_control](https://github.com/TUMFTM/mod_vehicle_dynamics_control) ⭐ 294 | 🐛 4 | 🌐 MATLAB | 📅 2022-03-19 - TUM Roborace Team Software Stack - Path tracking control, velocity control, curvature control and state estimation.
* [Aslan](https://github.com/project-aslan/Aslan) ⭐ 284 | 🐛 4 | 🌐 Python | 📅 2022-01-21 - Open source self-driving software for low speed environments.
* [mir\_robot](https://github.com/dfki-ric/mir_robot) ⭐ 277 | 🐛 11 | 🌐 Python | 📅 2026-04-27 - This is a community project to use the MiR Robots with ROS.
* [COMPAS](https://github.com/compas-dev/compas_fab) ⭐ 136 | 🐛 80 | 🌐 Python | 📅 2026-08-14 - Robotic fabrication package for the COMPAS Framework.
* [ROS](https://github.com/ros) - (Robot Operating System) provides libraries and tools to help software developers create robot applications.
* [Autoware.Auto](https://gitlab.com/autowarefoundation/autoware.auto) - Autoware.Auto applies best-in-class software engineering for autonomous driving.
* [Autoware.ai](https://github.com/Autoware-AI) - Autoware.AI is the world's first "All-in-One" open-source software for autonomous driving technology.
* [Stanford Self Driving Car Code](https://github.com/emmjaykay/stanford_self_driving_car_code) - Stanford Code From Cars That Entered DARPA Grand Challenges.
* [Automotive Grade Linux](https://www.automotivelinux.org/) - Automotive Grade Linux is a collaborative open source project that is bringing together automakers, suppliers and technology companies to accelerate the development and adoption of a fully open software stack for the connected car.
* [KubOS](https://github.com/kubos/kubos) - An open-source software stack for satellites.

## Development Environment

### Code and Run

* [Visual Studio Code](https://github.com/Microsoft/vscode) ⭐ 188,925 | 🐛 19,955 | 🌐 TypeScript | 📅 2026-08-19 - Code editor for edit-build-debug cycle.
* [atom](https://github.com/atom/atom) ⚠️ Archived - Hackable text editor for the 21st century.
* [pybind11](https://github.com/pybind/pybind11) ⭐ 18,001 | 🐛 713 | 🌐 C++ | 📅 2026-08-17 - Seamless operability between C++11 and Python.
* [Sourcetrail](https://github.com/CoatiSoftware/Sourcetrail) ⚠️ Archived - Free and open-source cross-platform source explorer.
* [Gitpod](https://github.com/gitpod-io/gitpod) ⭐ 13,751 | 🐛 456 | 🌐 TypeScript | 📅 2026-08-17 - An open source developer platform that automates the provisioning of ready-to-code development environments.
* [TabNine](https://github.com/zxqfl/TabNine) ⭐ 10,776 | 🐛 0 | 🌐 Shell | 📅 2025-09-04 - The all-language autocompleter.
* [jedi](https://github.com/davidhalter/jedi) ⭐ 6,171 | 🐛 70 | 🌐 Python | 📅 2026-07-09 - Autocompletion and static analysis library for python.
* [awesome-hpp](https://github.com/p-ranav/awesome-hpp) ⭐ 4,152 | 🐛 28 | 📅 2025-11-06 - A curated list of awesome header-only C++ libraries.
* [rebound](https://github.com/shobrook/rebound) ⭐ 4,115 | 🐛 24 | 🌐 Python | 📅 2022-02-16 - Command-line tool that instantly fetches Stack Overflow results when an exception is thrown.
* [xeus-cling](https://github.com/QuantStack/xeus-cling) ⭐ 3,291 | 🐛 179 | 🌐 C++ | 📅 2025-10-27 - Jupyter kernel for the C++ programming language.
* [Teletype](https://github.com/atom/teletype) ⚠️ Archived - Share your workspace with team members and collaborate on code in real time in Atom.
* [live-share](https://github.com/MicrosoftDocs/live-share) ⭐ 2,382 | 🐛 280 | 📅 2026-08-03 - Real-time collaborative development from the comfort of your favorite tools.
* [cocalc](https://github.com/sagemathinc/cocalc) ⭐ 1,287 | 🐛 1,503 | 🌐 TypeScript | 📅 2026-07-15 - Collaborative Calculation in the Cloud.
* [Jupyter ROS](https://github.com/RoboStack/jupyter-ros) ⭐ 613 | 🐛 30 | 🌐 Python | 📅 2026-04-02 - Jupyter widget helpers for ROS, the Robot Operating System.
* [EasyClangComplete](https://github.com/niosus/EasyClangComplete) ⭐ 580 | 🐛 26 | 🌐 Python | 📅 2026-06-09 - Robust C/C++ code completion for Sublime Text 3.
* [vscode-ros](https://github.com/ms-iot/vscode-ros) ⚠️ Archived - Visual Studio Code extension for Robot Operating System (ROS) development.
* [ros\_rqt\_plugin](https://github.com/ros-industrial/ros_qtc_plugin) ⭐ 429 | 🐛 20 | 🌐 C++ | 📅 2026-08-04 - The ROS Qt Creator Plug-in for Python.
* [roslibpy](https://github.com/gramaziokohler/roslibpy) ⭐ 333 | 🐛 16 | 🌐 Python | 📅 2026-08-03 - Python ROS Bridge library allows to use Python and IronPython to interact with ROS, the open-source robotic middleware.
* [Vim-ros](https://github.com/taketwo/vim-ros) ⭐ 133 | 🐛 0 | 🌐 Python | 📅 2025-02-19 - Vim plugin for ROS development.
* [recipe-wizard](https://github.com/trn84/recipe-wizard) ⭐ 43 | 🐛 4 | 🌐 Shell | 📅 2023-03-24 - A Dockerfile generator for running OpenGL (GLX) applications with nvidia-docker2, CUDA, ROS, and Gazebo on a remote headless server system.
* [Sublime](https://www.sublimetext.com/) - A sophisticated text editor for code, markup and prose.
* [ade-cli](https://gitlab.com/ApexAI/ade-cli) - The ADE Development Environment (ADE) uses docker and Gitlab to manage environments of per project development tools and optional volume images.
* [ROS IDEs](http://wiki.ros.org/IDEs) - This page collects experience and advice on using integrated development environments (IDEs) with ROS.
* [kite](https://kite.com/) - Use machine learning to give you useful code completions for Python.
* [mybinder](https://mybinder.org/) - Open notebooks in an executable environment, making your code immediately reproducible by anyone, anywhere.
* [ROSOnWindows](https://ms-iot.github.io/ROSOnWindows/) - An experimental release of ROS1 for Windows.

### Template

* [ROS](https://github.com/leggedrobotics/ros_best_practices/tree/master/ros_package_template) ⭐ 1,637 | 🐛 9 | 🌐 C++ | 📅 2022-01-22 - Template for ROS node standardization in C++.
* [Bash](https://github.com/ralish/bash-script-template) ⭐ 1,007 | 🐛 2 | 🌐 Shell | 📅 2026-02-15 - A bash scripting template incorporating best practices & several useful functions.
* [VS Code ROS2 Workspace Template](https://github.com/athackst/vscode_ros2_workspace) ⭐ 993 | 🐛 0 | 🌐 Python | 📅 2026-08-18 -  Template for using VSCode as an IDE for ROS2 development.
* [Launch](https://wiki.ros.org/roslaunch/Tutorials/Roslaunch%20tips%20for%20larger%20projects) - Templates on how to create launch files for larger projects.
* [URDF](https://wiki.ros.org/urdf/Examples) - Examples on how to create Unified Robot Description Format (URDF) for different kinds of robots.
* [Python](http://wiki.ros.org/PyStyleGuide) - Style guide to be followed in writing Python code for ROS.
* [Docker](https://ade-cli.readthedocs.io/en/latest/create-custom-base-image.html) - The Dockerfile in the minimal-ade project shows a minimal example of how to create a custom base image.

### Build and Deploy

* [pyenv](https://github.com/pyenv/pyenv) ⭐ 45,030 | 🐛 56 | 🌐 Shell | 📅 2026-08-16 - Simple Python version management.
* [clang](https://github.com/llvm-mirror/clang) ⚠️ Archived -  This is a compiler front-end for the C family of languages (C, C++, Objective-C, and Objective-C++) which is built as part of the LLVM compiler infrastructure project.
* [aptly](https://github.com/aptly-dev/aptly) ⭐ 2,871 | 🐛 212 | 🌐 Go | 📅 2026-08-09 - Debian repository management tool.
* [qemu-user-static](https://github.com/multiarch/qemu-user-static) ⭐ 2,710 | 🐛 66 | 🌐 Shell | 📅 2024-06-25 - Enable an execution of different multi-architecture containers by QEMU and binfmt\_misc.
* [docker\_images](https://github.com/osrf/docker_images) ⭐ 748 | 🐛 37 | 🌐 Dockerfile | 📅 2026-07-31 - Official Docker images maintained by OSRF on ROS(2) and Gazebo.
* [industrial\_ci](https://github.com/ros-industrial/industrial_ci) ⭐ 296 | 🐛 98 | 🌐 Shell | 📅 2026-06-01 - Easy continuous integration repository for ROS repositories.
* [robot\_upstart](https://github.com/clearpathrobotics/robot_upstart) ⭐ 205 | 🐛 45 | 🌐 Python | 📅 2026-01-26 - Presents a suite of scripts to assist with launching background ROS processes on Ubuntu Linux PCs.
* [cross\_compile](https://github.com/ros-tooling/cross_compile) ⚠️ Archived - Assets used for ROS2 cross-compilation.
* [catkin\_tools](https://github.com/catkin/catkin_tools) ⭐ 169 | 🐛 99 | 🌐 Python | 📅 2025-04-03 - Command line tools for working with catkin.
* [colcon-core](https://github.com/colcon/colcon-core) ⭐ 133 | 🐛 85 | 🌐 Python | 📅 2026-08-18 - Command line tool to improve the workflow of building, testing and using multiple software packages.
* [catkin\_virtualenv](https://github.com/locusrobotics/catkin_virtualenv) ⭐ 88 | 🐛 8 | 🌐 Python | 📅 2026-08-15 - Bundle python requirements in a catkin package via virtualenv.
* [bloom](https://github.com/ros-infrastructure/bloom) ⭐ 73 | 🐛 120 | 🌐 Python | 📅 2026-07-28 - A release automation tool which makes releasing catkin packages easier.
* [superflore](https://github.com/ros-infrastructure/superflore) ⭐ 61 | 🐛 21 | 🌐 Python | 📅 2026-01-15 - An extended platform release manager for Robot Operating System.
* [cros](https://github.com/ros-industrial/cros) ⭐ 50 | 🐛 10 | 🌐 C | 📅 2023-02-06 - A single thread pure C implementation of the ROS framework.
* [Cross compile ROS 2 on QNX](https://gitlab.apex.ai/snippets/97) -  Introduces how to cross compile ROS 2 on QNX.
* [ros\_gitlab\_ci](https://gitlab.com/VictorLamoine/ros_gitlab_ci) - Contains helper scripts and instructions on how to use Continuous Integration (CI) for ROS projects hosted on a GitLab instance.
* [gitlab-runner](https://gitlab.com/gitlab-org/gitlab-runner) -  Runs tests and sends the results to GitLab.
* [gitlab-release](https://gitlab.com/alelec/gitlab-release) - Simple python3 script to upload files (from ci) to the current projects release (tag).
* [robot\_systemd](http://docs.ros.org/kinetic/api/robot_systemd/html/#) - Units for managing startup and shutdown of roscore and roslaunch.
* [ryo-iso](https://ryo-iso.readthedocs.io/en/latest/) - A modern ISO builder that streamlines the process of deploying a complete robot operating system from a yaml config file.
* [network\_autoconfig](http://docs.ros.org/kinetic/api/network_autoconfig/html/) - Automatic configuration of ROS networking for most use cases without impacting usage that require manual configuration.
* [rosbuild](https://roscon.ros.org/2016/presentations/ROSCon2016%20Build%20Farm.pdf) - The ROS build farm.

### Unit and Integration Test

* [googletest](https://github.com/google/googletest) ⭐ 38,938 | 🐛 493 | 🌐 C++ | 📅 2026-08-18 - Google's C++ test framework.
* [pytest](https://github.com/pytest-dev/pytest/) ⭐ 14,429 | 🐛 810 | 🌐 Python | 📅 2026-08-19 - The pytest framework makes it easy to write small tests, yet scales to support complex functional testing.
* [doctest](https://github.com/onqtam/doctest) ⭐ 6,846 | 🐛 140 | 🌐 C++ | 📅 2026-08-18 - The fastest feature-rich C++11/14/17/20 single-header testing framework for unit tests and TDD.
* [action-ros-ci](https://github.com/ros-tooling/action-ros-ci) ⭐ 171 | 🐛 55 | 🌐 TypeScript | 📅 2026-05-15 - GitHub Action to build and test ROS 2 packages using colcon.
* [setup-ros](https://github.com/ros-tooling/setup-ros) ⭐ 108 | 🐛 34 | 🌐 TypeScript | 📅 2026-06-10 - This action sets up a ROS and ROS 2 environment for use in GitHub actions.
* [osrf\_testing\_tools\_cpp](https://github.com/osrf/osrf_testing_tools_cpp) ⭐ 38 | 🐛 11 | 🌐 C++ | 📅 2026-04-30 - Contains testing tools for C++, and is used in OSRF projects.
* [code\_coverage](https://github.com/mikeferguson/code_coverage) ⭐ 37 | 🐛 8 | 🌐 CMake | 📅 2023-08-29 - ROS package to run coverage testing.
* [UnitTesting](https://wiki.ros.org/Quality/Tutorials/UnitTesting) - This page lays out the rationale, best practices, and policies for writing and running unit tests and integration tests for ROS.

### Lint and Format

* [black](https://github.com/psf/black) ⭐ 41,807 | 🐛 304 | 🌐 Python | 📅 2026-08-19 - The uncompromising Python code formatter.
* [shellcheck](https://github.com/koalaman/shellcheck) ⭐ 39,893 | 🐛 1,139 | 🌐 Haskell | 📅 2026-08-04 - A static analysis tool for shell scripts.
* [pydantic](https://github.com/samuelcolvin/pydantic) ⭐ 28,568 | 🐛 576 | 🌐 Python | 📅 2026-08-19 - Data parsing and validation using Python type hints.
* [hadolint](https://github.com/hadolint/hadolint) ⭐ 12,363 | 🐛 203 | 🌐 Haskell | 📅 2026-08-17 - Dockerfile linter, validate inline bash, written in Haskell.
* [cppcheck](https://github.com/danmar/cppcheck) ⭐ 6,720 | 🐛 201 | 🌐 C++ | 📅 2026-08-18 - Static analysis of C/C++ code.
* [pylint](https://github.com/PyCQA/pylint/) ⭐ 5,712 | 🐛 1,080 | 🌐 Python | 📅 2026-08-19 - Pylint is a Python static code analysis tool which looks for programming errors, helps enforcing a coding standard, sniffs for code smells and offers simple refactoring suggestions.
* [pydocstyle](https://github.com/PyCQA/pydocstyle) ⚠️ Archived - A static analysis tool for checking compliance with Python docstring conventions.
* [haros](https://github.com/git-afsantos/haros) ⭐ 200 | 🐛 1 | 🌐 Python | 📅 2024-12-12 - Static analysis of ROS application code.
* [catkin\_lint](https://github.com/fkie/catkin_lint) ⭐ 57 | 🐛 1 | 🌐 Python | 📅 2024-12-10 - Checks package configurations for the catkin build system of ROS.
* [action-ros-lint](https://github.com/ros-tooling/action-ros-lint) ⭐ 20 | 🐛 5 | 🌐 TypeScript | 📅 2024-12-16 - GitHub action to run linters on ROS 2 packages.

### Debugging and Tracing

* [bcc](https://github.com/iovisor/bcc) ⭐ 22,626 | 🐛 1,069 | 🌐 C | 📅 2026-08-14 - Tools for BPF-based Linux IO analysis, networking, monitoring, and more.
* [FlameGraph](https://github.com/brendangregg/FlameGraph) ⭐ 19,681 | 🐛 174 | 🌐 Perl | 📅 2024-10-20 - Visualize profiled code.
* [tracy](https://github.com/wolfpld/tracy) ⭐ 16,621 | 🐛 181 | 🌐 C++ | 📅 2026-08-18 - A real time, nanosecond resolution, remote telemetry frame profiler for games and other applications.
* [sanitizer](https://github.com/google/sanitizers) ⭐ 12,449 | 🐛 548 | 🌐 C | 📅 2026-05-19 - AddressSanitizer, ThreadSanitizer, MemorySanitizer.
* [gdb-dashboard](https://github.com/cyrus-and/gdb-dashboard) ⭐ 12,242 | 🐛 19 | 🌐 Python | 📅 2026-07-17 - GDB dashboard is a standalone .gdbinit file written using the Python API that enables a modular interface showing relevant information about the program being debugged.
* [bpftrace](https://github.com/iovisor/bpftrace) ⭐ 10,287 | 🐛 249 | 🌐 C++ | 📅 2026-08-19 - High-level tracing language for Linux eBPF.
* [vscode-debug-visualizer](https://github.com/hediet/vscode-debug-visualizer) ⭐ 8,168 | 🐛 107 | 🌐 TypeScript | 📅 2025-03-17 - An extension for VS Code that visualizes data during debugging.
* [pyre-check](https://github.com/facebook/pyre-check) ⚠️ Archived - Performant type-checking for python.
* [hotspot](https://github.com/KDAB/hotspot) ⭐ 5,131 | 🐛 81 | 🌐 C++ | 📅 2026-05-12 - The Linux perf GUI for performance analysis.
* [memory\_profiler](https://github.com/pythonprofilers/memory_profiler) ⭐ 4,575 | 🐛 141 | 🌐 Python | 📅 2024-04-29 - A python module for monitoring memory consumption of a process as well as line-by-line analysis of memory consumption for python programs.
* [cppinsights](https://github.com/andreasfertig/cppinsights) ⭐ 4,519 | 🐛 25 | 🌐 C++ | 📅 2026-08-02 - C++ Insights - See your source code with the eyes of a compiler.
* [backward-cpp](https://github.com/bombela/backward-cpp) ⭐ 4,300 | 🐛 126 | 🌐 C++ | 📅 2025-04-14 - A beautiful stack trace pretty printer for C++.
* [heaptrack](https://github.com/KDE/heaptrack) ⭐ 4,152 | 🐛 6 | 🌐 C++ | 📅 2026-08-12 - Traces all memory allocations and annotates these events with stack traces.
* [qira](https://github.com/geohot/qira) ⭐ 4,069 | 🐛 69 | 🌐 C | 📅 2022-07-02 - QIRA is a competitor to strace and gdb.
* [action-tmate](https://github.com/mxschmitt/action-tmate) ⭐ 3,577 | 🐛 36 | 🌐 JavaScript | 📅 2026-07-29 - Debug your GitHub Actions via SSH by using tmate to get access to the runner system itself.
* [pudb](https://github.com/inducer/pudb) ⭐ 3,251 | 🐛 164 | 🌐 Python | 📅 2026-08-16 - Full-screen console debugger for Python.
* [gdb-frontend](https://github.com/rohanrhu/gdb-frontend) ⭐ 3,027 | 🐛 16 | 🌐 JavaScript | 📅 2025-11-12 - GDBFrontend is an easy, flexible and extensionable gui debugger.
* [pyperformance](https://github.com/python/pyperformance) ⭐ 1,027 | 🐛 72 | 🌐 Python | 📅 2026-08-17 - Python Performance Benchmark Suite.
* [gpuvis](https://github.com/mikesart/gpuvis) ⭐ 903 | 🐛 6 | 🌐 C++ | 📅 2026-01-14 - GPU Trace Visualizer.
* [lptrace](https://github.com/khamidou/lptrace) ⭐ 699 | 🐛 7 | 🌐 Python | 📅 2018-10-26 - It lets you see in real-time what functions a Python program is running.
* [ros2-performance](https://github.com/irobot-ros/ros2-performance) ⭐ 407 | 🐛 6 | 🌐 C++ | 📅 2026-05-31 - Allows to easily create arbitrary ROS2 systems and then measures their performance.
* [libstatistics\_collector](https://github.com/ros-tooling/libstatistics_collector) ⭐ 40 | 🐛 4 | 🌐 C++ | 📅 2026-07-01 - ROS 2 library providing classes to collect measurements and calculate statistics across them.
* [system\_metrics\_collector](https://github.com/ros-tooling/system_metrics_collector) ⚠️ Archived - Lightweight, real-time system metrics collector for ROS2 systems.
* [ros1\_fuzzer](https://github.com/aliasrobotics/ros1_fuzzer) ⚠️ Archived - This fuzzer aims to help developers and researchers to find bugs and vulnerabilities in ROS nodes by performing fuzz tests over topics that the target nodes process.
* [ros2\_tracing](https://gitlab.com/ros-tracing/ros2_tracing) - Tracing tools for ROS 2.
* [Linuxperf](http://www.brendangregg.com/linuxperf.html) - Various Linux performance material.
* [inspect](https://pymotw.com/2/inspect/) - The inspect module provides functions for learning about live objects, including modules, classes, instances, functions, and methods.
* [Roslaunch Nodes in Valgrind or GDB](https://wiki.ros.org/roslaunch/Tutorials/Roslaunch%20Nodes%20in%20Valgrind%20or%20GDB) - When debugging roscpp nodes that you are launching with roslaunch, you may wish to launch the node in a debugging program like gdb or valgrind instead.
* [lttng](https://lttng.org/docs/) - An open source software toolkit which you can use to simultaneously trace the Linux kernel, user applications, and user libraries.

### Version Control

* [lazygit](https://github.com/jesseduffield/lazygit) ⭐ 81,459 | 🐛 1,025 | 🌐 Go | 📅 2026-08-19 - A simple terminal UI for git commands, written in Go with the gocui library.
* [dive](https://github.com/wagoodman/dive) ⭐ 54,474 | 🐛 211 | 🌐 Go | 📅 2025-12-15 - A tool for exploring each layer in a docker image.
* [learnGitBranching](https://github.com/pcottle/learnGitBranching) ⭐ 33,900 | 🐛 61 | 🌐 JavaScript | 📅 2026-08-19 - A git repository visualizer, sandbox, and a series of educational tutorials and challenges.
* [semantic-release](https://github.com/semantic-release/semantic-release) ⭐ 23,987 | 🐛 405 | 🌐 JavaScript | 📅 2026-08-18 - Fully automated version management and package publishing.
* [dvc](https://github.com/iterative/dvc) ⭐ 15,828 | 🐛 199 | 🌐 Python | 📅 2026-08-19 - Management and versioning of datasets and machine learning models.
* [tig](https://github.com/jonas/tig) ⭐ 13,307 | 🐛 226 | 🌐 C | 📅 2026-07-27 - Text-mode interface for git.
* [bfg-repo-cleaner](https://github.com/rtyley/bfg-repo-cleaner) ⭐ 12,168 | 🐛 275 | 🌐 Scala | 📅 2025-01-19 - Removes large or troublesome blobs like git-filter-branch does, but faster.
* [git-secret](https://github.com/sobolevn/git-secret) ⭐ 4,036 | 🐛 251 | 🌐 Shell | 📅 2026-08-11 - Encrypts files with permitted users' public keys, allowing users you trust to access encrypted data using pgp and their secret keys.
* [nbdime](https://github.com/jupyter/nbdime) ⭐ 2,840 | 🐛 94 | 🌐 TypeScript | 📅 2026-06-10 - Tools for diffing and merging of Jupyter notebooks.
* [git-sweep](https://github.com/arc90/git-sweep) ⭐ 2,704 | 🐛 45 | 🌐 Python | 📅 2023-10-01 - A command-line tool that helps you clean up Git branches that have been merged into master.
* [gitfs](https://github.com/Presslabs/gitfs) ⭐ 2,594 | 🐛 71 | 🌐 Python | 📅 2026-04-13 - You can mount a remote repository's branch locally, and any subsequent changes made to the files will be automatically committed to the remote.
* [git-cola](https://github.com/git-cola/git-cola) ⭐ 2,561 | 🐛 5 | 🌐 Python | 📅 2026-08-16 - The highly caffeinated Git GUI.
* [python-gitlab](https://github.com/python-gitlab/python-gitlab) ⭐ 2,471 | 🐛 31 | 🌐 Python | 📅 2026-08-17 - A Python package providing access to the GitLab server API.
* [git-fuzzy](https://github.com/bigH/git-fuzzy) ⭐ 2,435 | 🐛 2 | 🌐 Shell | 📅 2026-06-19 - A CLI interface to git that relies heavily on fzf.
* [glab](https://github.com/profclems/glab) ⚠️ Archived - An open-source GitLab command line tool.
* [meld](https://github.com/GNOME/meld) ⭐ 1,304 | 🐛 0 | 🌐 Python | 📅 2026-08-15 - Meld is a visual diff and merge tool that helps you compare files, directories, and version controlled projects.
* [gitg](https://github.com/GNOME/gitg) ⭐ 216 | 🐛 0 | 🌐 Vala | 📅 2026-07-30 - A graphical user interface for git.
* [go-semrel-gitab](https://gitlab.com/juhani/go-semrel-gitlab) - Automate version management for Gitlab.
* [Git-repo](https://gerrit.googlesource.com/git-repo/) - Git-Repo helps manage many Git repositories, does the uploads to revision control systems, and automates parts of the development workflow.

## Simulation

* [AirSim](https://github.com/microsoft/AirSim) ⭐ 18,408 | 🐛 780 | 🌐 C++ | 📅 2026-06-30 - Open source simulator for autonomous vehicles built on Unreal Engine.
* [carla](https://github.com/carla-simulator/carla) ⭐ 14,302 | 🐛 1,192 | 🌐 C++ | 📅 2026-08-19 - Open-source simulator for autonomous driving research.
* [Webots](https://github.com/cyberbotics/webots) ⭐ 4,563 | 🐛 229 | 🌐 C++ | 📅 2026-08-18 - Webots is an open source robot simulator compatible (among others) with [ROS](http://wiki.ros.org/webots_ros) and [ROS2](http://wiki.ros.org/webots_ros2).
* [Drake](https://github.com/RobotLocomotion/drake) ⭐ 4,155 | 🐛 655 | 🌐 C++ | 📅 2026-08-19 - Drake aims to simulate even very complex dynamics of robots.
* [sumo](https://github.com/eclipse/sumo) ⭐ 4,134 | 🐛 2,977 | 🌐 Python | 📅 2026-08-19 - Eclipse SUMO is an open source, highly portable, microscopic and continuous road traffic simulation package designed to handle large road networks.
* [self-driving-car-sim](https://github.com/udacity/self-driving-car-sim) ⚠️ Archived - A self-driving car simulator built with Unity.
* [OpenSceneGraph](https://github.com/openscenegraph/OpenSceneGraph) ⭐ 3,602 | 🐛 176 | 🌐 C++ | 📅 2024-08-09 - An open source high performance 3D graphics toolkit, used by application developers in fields such as visual simulation, games, virtual reality, scientific visualization and modelling.
* [highway-env](https://github.com/eleurent/highway-env) ⭐ 3,298 | 🐛 41 | 🌐 Python | 📅 2026-08-07 - A collection of environments for autonomous driving and tactical decision-making tasks.
* [Unity-Robotics-Hub](https://github.com/Unity-Technologies/Unity-Robotics-Hub) ⭐ 2,561 | 🐛 57 | 🌐 C# | 📅 2024-11-26 - Central repository for tools, tutorials, resources, and documentation for robotic simulation in Unity.
* [simbody](https://github.com/simbody/simbody) ⭐ 2,544 | 🐛 161 | 🌐 C++ | 📅 2026-08-12 - High-performance C++ multibody dynamics/physics library for simulating articulated biomechanical and mechanical systems like vehicles, robots, and the human skeleton.
* [lgsv](https://github.com/lgsvl/simulator) ⭐ 2,456 | 🐛 628 | 🌐 C# | 📅 2023-04-04 - LG Electronics America R\&D Center has developed an HDRP Unity-based multi-robot simulator for autonomous vehicle developers.
* [champ](https://github.com/chvmp/champ) ⭐ 2,300 | 🐛 55 | 🌐 C++ | 📅 2024-07-04 - ROS Packages for CHAMP Quadruped Controller.
* [gym-pybullet-drones](https://github.com/utiasDSL/gym-pybullet-drones) ⭐ 2,109 | 🐛 110 | 🌐 Python | 📅 2026-08-16 - PyBullet-based Gym environments for single and multi-agent reinforcement learning of quadcopter control.
* [AI2-THOR](https://github.com/allenai/ai2thor) ⭐ 1,783 | 🐛 279 | 🌐 C# | 📅 2025-11-04 - Python framework with a Unity backend providing interaction, navigation, and manipulation support for household based robotic agents, consisting of 200+ of custom scenes, 1500+ custom annotated objects, and 200+ actions.
* [rotors\_simulator](https://github.com/ethz-asl/rotors_simulator) ⭐ 1,502 | 🐛 174 | 🌐 C++ | 📅 2024-07-15 - Provides some multirotor models.
* [gnss-ins-sim](https://github.com/Aceinna/gnss-ins-sim) ⭐ 1,482 | 🐛 1 | 🌐 Python | 📅 2024-11-27 - GNSS + inertial navigation, sensor fusion simulator. Motion trajectory generator, sensor models, and navigation.
* [flightmare](https://github.com/uzh-rpg/flightmare) ⭐ 1,403 | 🐛 128 | 🌐 C++ | 📅 2024-06-14 - Flightmare is composed of two main components: a configurable rendering engine built on Unity and a flexible physics engine for dynamics simulation.
* [gazebo\_models](https://github.com/osrf/gazebo_models) ⭐ 1,303 | 🐛 29 | 🌐 HTML | 📅 2024-07-14 - This repository holds the Gazebo model database.
* [flow](https://github.com/flow-project/flow) ⭐ 1,188 | 🐛 215 | 🌐 Python | 📅 2024-07-27 - A computational framework for deep RL and control experiments for traffic microsimulation.
* [OpenCDA](https://github.com/ucla-mobility/OpenCDA) ⭐ 1,162 | 🐛 30 | 🌐 Python | 📅 2026-08-18 - A generalized framework for prototyping full-stack cooperative driving automation applications under CARLA+SUMO.
* [rex-gym](https://github.com/nicrusso7/rex-gym) ⭐ 1,101 | 🐛 13 | 🌐 Python | 📅 2023-03-24 - OpenAI Gym environments for an open-source quadruped robot (SpotMicro).
* [esmini](https://github.com/esmini/esmini) ⭐ 941 | 🐛 218 | 🌐 C++ | 📅 2026-08-19 -  A basic OpenSCENARIO player.
* [deepdive](https://github.com/deepdrive/deepdrive) ⭐ 926 | 🐛 40 | 🌐 Python | 📅 2023-10-03 - End-to-end simulation for self-driving cars.
* [awesome-CARLA](https://github.com/Amin-Tgz/awesome-CARLA) ⭐ 916 | 🐛 0 | 📅 2024-03-27 - A curated list of awesome CARLA tutorials, blogs, and related projects.
* [safe-control-gym](https://github.com/utiasDSL/safe-control-gym) ⭐ 909 | 🐛 6 | 🌐 Python | 📅 2026-04-29 - PyBullet-based CartPole and Quadrotor environments—with CasADi symbolic dynamics and constraints—for safe and robust learning-based control.
* [uuv\_simulator](https://github.com/uuvsimulator/uuv_simulator) ⚠️ Archived - Gazebo/ROS packages for underwater robotics simulation.
* [gym-gazebo](https://github.com/erlerobot/gym-gazebo) ⚠️ Archived - An OpenAI gym extension for using Gazebo known as gym-gazebo.
* [ESIM](https://github.com/uzh-rpg/rpg_esim/) ⭐ 725 | 🐛 83 | 🌐 C | 📅 2023-12-25 - An Open Event Camera Simulator.
* [scenario\_runner](https://github.com/carla-simulator/scenario_runner) ⭐ 679 | 🐛 180 | 🌐 Python | 📅 2026-07-29 - Traffic scenario definition and execution engine.
* [ros-bridge](https://github.com/carla-simulator/ros-bridge) ⭐ 643 | 🐛 185 | 🌐 Python | 📅 2026-08-16 - ROS bridge for CARLA Simulator.
* [gym-carla](https://github.com/cjy1992/gym-carla) ⭐ 617 | 🐛 35 | 🌐 Python | 📅 2022-02-14 - An OpenAI gym wrapper for CARLA simulator.
* [pedsim\_ros](https://github.com/srl-freiburg/pedsim_ros) ⭐ 587 | 🐛 34 | 🌐 C++ | 📅 2023-08-07 - Pedestrian simulator powered by the social force model for Gazebo.
* [car\_demo](https://github.com/osrf/car_demo) ⚠️ Archived - This is a simulation of a Prius in gazebo 9 with sensor data being published using ROS kinetic.
* [BlueSky](https://github.com/TUDelft-CNS-ATM/bluesky) ⭐ 553 | 🐛 56 | 🌐 Python | 📅 2026-07-21 - The goal of BlueSky is to provide everybody who wants to visualize, analyze or simulate air traffic with a tool to do so without any restrictions, licenses or limitations.
* [pylot](https://github.com/erdos-project/pylot) ⭐ 535 | 🐛 51 | 🌐 Python | 📅 2023-03-24 - Autonomous driving platform running on the CARLA simulator.
* [ROSIntegration](https://github.com/code-iai/ROSIntegration) ⭐ 466 | 🐛 55 | 🌐 C++ | 📅 2025-11-03 - Unreal Engine Plugin to enable ROS Support.
* [usv\_sim\_lsa](https://github.com/disaster-robotics-proalertas/usv_sim_lsa) ⭐ 457 | 🐛 37 | 🌐 Python | 📅 2024-07-07 - Unmanned Surface Vehicle simulation on Gazebo with water current and winds.
* [42](https://github.com/ericstoneking/42) ⭐ 449 | 🐛 26 | 🌐 C | 📅 2026-08-13 - Simulation for spacecraft attitude control system analysis and design.
* [open-simulation-interface](https://github.com/OpenSimulationInterface/open-simulation-interface) ⭐ 301 | 🐛 185 | 🌐 Python | 📅 2026-08-13 - A generic interface for the environmental perception of automated driving functions in virtual scenarios.
* [Complete\_Street\_Rule](https://github.com/d-wasserman/Complete_Street_Rule) ⭐ 217 | 🐛 2 | 🌐 Python | 📅 2026-03-23 - A scenario oriented design tool intended to enable users to quickly create procedurally generated multimodal streets in ArcGIS CityEngine.
* [map2gazebo](https://github.com/shilohc/map2gazebo) ⭐ 180 | 🐛 8 | 🌐 Python | 📅 2022-10-02 - ROS package for creating Gazebo environments from 2D maps.
* [Dynamic\_logistics\_Warehouse](https://github.com/belal-ibrahim/dynamic_logistics_warehouse) ⭐ 179 | 🐛 2 | 🌐 CMake | 📅 2021-07-13 - Gazebo simulation of dynamics environment in warehouses.
* [Trick](https://github.com/nasa/Trick) ⭐ 161 | 🐛 110 | 🌐 C++ | 📅 2026-08-13 - Developed at the NASA Johnson Space Center, is a powerful simulation development framework that enables users to build applications for all phases of space vehicle development.
* [Menge](https://github.com/MengeCrowdSim/Menge) ⭐ 154 | 🐛 71 | 🌐 C++ | 📅 2025-12-02 - Crowd Simulation Framework.
* [sim\_vehicle\_dynamics](https://github.com/TUMFTM/sim_vehicle_dynamics) ⭐ 148 | 🐛 3 | 🌐 MATLAB | 📅 2022-06-22 - Vehicle Dynamics Simulation Software of TUM Roborace Team.
* [gazebo\_ros\_motors](https://github.com/nilseuropa/gazebo_ros_motors) ⭐ 137 | 🐛 4 | 🌐 C++ | 📅 2024-08-13 - Contains currently two motor plugins for Gazebo, one with an ideal speed controller and one without a controller that models a DC motor.
* [fetch\_gazebo](https://github.com/fetchrobotics/fetch_gazebo) ⭐ 109 | 🐛 19 | 🌐 Python | 📅 2024-06-04 - Contains the Gazebo simulation for Fetch Robotics Fetch and Freight Research Edition Robots.
* [fields-ignition](https://github.com/azazdeaz/fields-ignition) ⭐ 86 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2020-11-14 - Generate random crop fields for Ignition Gazebo.
* [ROSIntegrationVision](https://github.com/code-iai/ROSIntegrationVision) ⭐ 82 | 🐛 10 | 🌐 C++ | 📅 2023-07-14 - Support for ROS-enabled RGBD data acquisition in Unreal Engine Projects.
* [Cloe](https://github.com/eclipse/cloe) ⭐ 49 | 🐛 46 | 🌐 C++ | 📅 2026-04-16 - Empowers developers of automated-driving software components by providing a unified interface to closed-loop simulation.
* [VREP Interface](http://www.coppeliarobotics.com/helpFiles/en/rosInterf.htm) - ROS Bridge for the VREP simulator.
* [opencrg](http://www.opencrg.org/download.html) -  Open file formats and open source tools for the detailed description, creation and evaluation of road surfaces.
* [morse](https://github.com/morse-simulator) - An academic robotic simulator, based on the Blender Game Engine and the Bullet Physics engine.
* [Ignition Robotics](https://ignitionrobotics.org) -  Test control strategies in safety, and take advantage of simulation in continuous integration tests.
* [simulation assets for the SubT](https://subtchallenge.world/openrobotics/fuel/collections/SubT%20Tech%20Repo) - This collection contains simulation assets for the SubT Challenge Virtual Competition in Gazebo.
* [AutoCore simulation](https://github.com/autowarefoundation/) - Provides test environment for Autoware and still during early development, contents below may changed during updates.

## Electronics and Mechanics

* [FreeCAD](https://github.com/FreeCAD/FreeCAD) ⭐ 32,939 | 🐛 4,085 | 🌐 C++ | 📅 2026-08-19 - Your own 3D parametric modeler.
* [openscad](https://github.com/openscad/openscad) ⭐ 9,976 | 🐛 824 | 🌐 C++ | 📅 2026-08-19 -  A software for creating solid 3D CAD models.
* [WireViz](https://github.com/formatc1702/WireViz) ⭐ 5,225 | 🐛 193 | 🌐 Python | 📅 2026-06-06 - A tool for easily documenting cables, wiring harnesses and connector pinouts.
* [NASA-3D-Resources](https://github.com/nasa/NASA-3D-Resources) ⭐ 3,750 | 🐛 5 | 📅 2025-06-03 - Here you'll find a growing collection of 3D models, textures, and images from inside NASA.
* [ODrive](https://github.com/madcowswe/ODrive) ⭐ 3,736 | 🐛 18 | 🌐 C++ | 📅 2026-01-20 - The aim is to make it possible to use inexpensive brushless motors in high performance robotics projects.
* [LibrePCB](https://github.com/LibrePCB/LibrePCB) ⭐ 2,968 | 🐛 217 | 🌐 C++ | 📅 2026-08-12 - A powerful, innovative and intuitive EDA tool for everyone.
* [GNSS-SDR](https://github.com/gnss-sdr/gnss-sdr) ⭐ 2,208 | 🐛 236 | 🌐 C++ | 📅 2026-08-09 - GNSS-SDR provides interfaces for a wide range of radio frequency front-ends and raw sample file formats, generates processing outputs in standard formats.
* [pvlib-python](https://github.com/pvlib/pvlib-python) ⭐ 1,639 | 🐛 241 | 🌐 Python | 📅 2026-08-19 - A community supported tool that provides a set of functions and classes for simulating the performance of photovoltaic energy systems.
* [PcbDraw](https://github.com/yaqwsx/PcbDraw) ⭐ 1,409 | 🐛 10 | 🌐 Python | 📅 2026-08-07 - Convert your KiCAD board into a nice looking 2D drawing suitable for pinout diagrams.
* [Horizon](https://github.com/horizon-eda/horizon) ⭐ 1,310 | 🐛 162 | 🌐 C | 📅 2026-07-28 - EDA is an Electronic Design Automation package supporting an integrated end-to-end workflow for printed circuit board design including parts management and schematic entry.
* [phobos](https://github.com/dfki-ric/phobos) ⭐ 899 | 🐛 14 | 🌐 Python | 📅 2026-07-14 - An add-on for Blender allowing to create URDF, SDF and SMURF robot models in a WYSIWYG environment.
* [kicad-3rd-party-tools](https://github.com/xesscorp/kicad-3rd-party-tools) ⭐ 838 | 🐛 3 | 📅 2026-05-15 - Tools made by others to augment the KiCad PCB EDA suite.
* [OpenMDAO](https://github.com/OpenMDAO/OpenMDAO) ⭐ 770 | 🐛 80 | 🌐 Python | 📅 2026-08-15 - An open-source framework for efficient multidisciplinary optimization.
* [solidworks\_urdf\_exporter](https://github.com/ros/solidworks_urdf_exporter) ⭐ 665 | 🐛 48 | 🌐 C# | 📅 2026-06-05 - SolidWorks to URDF Exporter.
* [cadCAD](https://github.com/cadCAD-org/cadCAD) ⭐ 613 | 🐛 11 | 🌐 Python | 📅 2024-04-19 - A Python package that assists in the processes of designing, testing and validating complex systems through simulation, with support for Monte Carlo methods, A/B testing and parameter sweeping.
* [urdf-viz](https://github.com/OTL/urdf-viz) ⭐ 587 | 🐛 17 | 🌐 Rust | 📅 2026-06-19 - Visualize URDF/XACRO file, URDF Viewer works on Windows/macOS/Linux.
* [FMPy](https://github.com/CATIA-Systems/FMPy) ⭐ 585 | 🐛 141 | 🌐 Python | 📅 2026-08-13 - Simulate Functional Mockup Units (FMUs) in Python.
* [SUAVE](https://github.com/suavecode/SUAVE) ⭐ 526 | 🐛 39 | 🌐 ReScript | 📅 2024-02-14 - An Aircraft Design Toolbox.
* [oemof-solph](https://github.com/oemof/oemof-solph) ⭐ 415 | 🐛 118 | 🌐 Python | 📅 2026-08-19 - A modular open source framework to model energy supply systems.
* [Inkscape Ray Optics](https://github.com/damienBloch/inkscape-raytracing) ⭐ 377 | 🐛 9 | 🌐 Python | 📅 2024-06-20 - An extension for Inkscape that makes it easier to draw optical diagrams.
* [urdfpy](https://github.com/mmatl/urdfpy) ⭐ 320 | 🐛 30 | 🌐 Python | 📅 2024-08-19 - A simple and easy-to-use library for loading, manipulating, saving, and visualizing URDF files.
* [tigl](https://github.com/DLR-SC/tigl) ⭐ 301 | 🐛 137 | 🌐 C++ | 📅 2026-08-19 - The TiGL Geometry Library can be used for the computation and processing of aircraft geometries stored inside CPACS files.
* [OpenAeroStruct](https://github.com/mdolab/OpenAeroStruct) ⭐ 277 | 🐛 34 | 🌐 Python | 📅 2025-10-06 -  A lightweight tool that performs aerostructural optimization using OpenMDAO.
* [opem](https://github.com/ECSIM/opem) ⭐ 232 | 🐛 2 | 🌐 Python | 📅 2026-08-17 - The Open-Source PEMFC Simulation Tool (OPEM) is a modeling tool for evaluating the performance of proton exchange membrane fuel cells.
* [FMIKit-Simulink](https://github.com/CATIA-Systems/FMIKit-Simulink) ⚠️ Archived - Import and export Functional Mock-up Units with Simulink.
* [URDF](https://github.com/ros/urdf) ⚠️ Archived - Repository for Unified Robot Description Format (URDF) parsing code.
* [HRIM](https://github.com/AcutronicRobotics/HRIM) ⚠️ Archived - An information model for robot hardware.
* [OpenTirePython](https://github.com/OpenTire/OpenTirePython) ⭐ 67 | 🐛 4 | 🌐 Python | 📅 2020-06-26 - An open-source mathematical tire modelling library.
* [foxBMS](https://github.com/foxBMS/foxbms) ⭐ 9 | 🐛 0 | 📅 2024-04-05 - A free, open and flexible development environment to design battery management systems.
* [kicad](http://www.kicad.org/) - A Cross Platform and Open Source Electronics Design Automation Suite.
* [PandaPower](http://www.pandapower.org) - An easy to use open source tool for power system modeling, analysis and optimization with a high degree of automation.
* [ngspice](http://ngspice.sourceforge.net/) - A open source spice simulator for electric and electronic circuits.
* [riscv](https://riscv.org) - The Free and Open RISC Instruction Set Architecture.

## Sensor Processing

### Calibration and Transformation

* [kalibr](https://github.com/ethz-asl/kalibr) ⭐ 5,650 | 🐛 135 | 🌐 C++ | 📅 2024-03-30 - The Kalibr visual-inertial calibration toolbox.
* [lidar\_camera\_calibration](https://github.com/ankitdhall/lidar_camera_calibration) ⭐ 1,765 | 🐛 61 | 🌐 C++ | 📅 2025-10-16 - ROS package to find a rigid-body transformation between a LiDAR and a camera.
* [imu\_utils](https://github.com/gaowenliang/imu_utils) ⭐ 1,732 | 🐛 35 | 🌐 C++ | 📅 2026-03-19 - A ROS package tool to analyze the IMU performance.
* [easy\_handeye](https://github.com/IFL-CAMP/easy_handeye) ⭐ 1,168 | 🐛 23 | 🌐 Python | 📅 2025-11-30 - Simple, straighforward ROS library for hand-eye calibration.
* [lidar\_align](https://github.com/ethz-asl/lidar_align) ⭐ 1,049 | 🐛 29 | 🌐 C++ | 📅 2025-03-11 - A simple method for finding the extrinsic calibration between a 3D lidar and a 6-dof pose sensor.
* [ikpy](https://github.com/Phylliade/ikpy) ⭐ 1,026 | 🐛 24 | 🌐 Python | 📅 2026-08-08 - An Inverse Kinematics library aiming performance and modularity.
* [lidar\_camera\_calibration](https://github.com/heethesh/lidar_camera_calibration) ⭐ 684 | 🐛 37 | 🌐 Python | 📅 2021-03-27 - Camera LiDAR Calibration using ROS, OpenCV, and PCL.
* [kalibr\_allan](https://github.com/rpng/kalibr_allan) ⚠️ Archived - IMU Allan standard deviation charts for use with Kalibr and inertial kalman filters.
* [livox\_camera\_lidar\_calibration](https://github.com/Livox-SDK/livox_camera_lidar_calibration) ⭐ 635 | 🐛 41 | 🌐 C++ | 📅 2021-09-24 - Calibrate the extrinsic parameters between Livox LiDAR and camera.
* [multi\_sensor\_calibration](https://github.com/tudelft-iv/multi_sensor_calibration/) ⭐ 556 | 🐛 30 | 🌐 C++ | 📅 2023-07-18 - Contains a calibration tool to calibrate a sensor setup consisting of lidars, radars and cameras.
* [robot\_calibration](https://github.com/mikeferguson/robot_calibration/) ⭐ 488 | 🐛 7 | 🌐 C++ | 📅 2026-08-10 - This package offers calibration of a number of parameters of a robot, such as: 3D Camera intrinsics, extrinsics Joint angle offsets and robot frame offsets.
* [ILCC](https://github.com/mfxox/ILCC) ⭐ 473 | 🐛 13 | 🌐 Python | 📅 2024-07-08 - Reflectance Intensity Assisted Automatic and Accurate Extrinsic Calibration of 3D LiDAR.
* [pyquaternion](https://github.com/KieranWynn/pyquaternion) ⭐ 366 | 🐛 37 | 🌐 Python | 📅 2026-05-07 - A full-featured Python module for representing and using quaternions.
* [LiDARTag](https://github.com/UMich-BipedLab/LiDARTag) ⭐ 285 | 🐛 6 | 🌐 C++ | 📅 2023-06-01 - A Real-Time Fiducial Tag using Point Clouds Lidar Data.
* [Calibnet](https://github.com/epiception/CalibNet) ⭐ 229 | 🐛 9 | 🌐 Python | 📅 2023-08-17 - Self-Supervised Extrinsic Calibration using 3D Spatial Transformer Networks.
* [e2calib](https://github.com/uzh-rpg/e2calib) ⭐ 198 | 🐛 3 | 🌐 Python | 📅 2025-02-28 - Contains code that implements video reconstruction from event data for calibration.
* [multicam\_calibration](https://github.com/KumarRobotics/multicam_calibration) ⭐ 135 | 🐛 0 | 🌐 C++ | 📅 2023-02-14 - Extrinsic and intrinsic calbration of cameras.
* [TriP](https://github.com/TriPed-Robot/TriP) ⭐ 43 | 🐛 21 | 🌐 Python | 📅 2022-05-06 - A Inverse Kinematics library for serial robots, parallel robots and hybrids of both.
* [tf2](http://wiki.ros.org/tf2) - Transform library, which lets the user keep track of multiple coordinate frames over time.

### Perception Pipeline

* [GibsonEnv](https://github.com/StanfordVL/GibsonEnv) ⭐ 945 | 🐛 49 | 🌐 C | 📅 2024-04-15 - Gibson Environments: Real-World Perception for Embodied Agents.
* [multiple-object-tracking-lidar](https://github.com/praveen-palanisamy/multiple-object-tracking-lidar) ⭐ 902 | 🐛 12 | 🌐 C++ | 📅 2022-06-22 - C++ implementation to Detect, track and classify multiple objects using LIDAR scans or point cloud.
* [cadrl\_ros](https://github.com/mfe7/cadrl_ros) ⭐ 723 | 🐛 3 | 🌐 Python | 📅 2021-12-23 - ROS package for dynamic obstacle avoidance for ground robots trained with deep RL.
* [se(3)-TrackNet](https://github.com/wenbowen123/iros20-6d-pose-tracking) ⭐ 423 | 🐛 10 | 🌐 Python | 📅 2023-08-30 - A package for 6D pose tracking of dynamic objects when object's CAD model is available.
* [AugmentedAutoencoder](https://github.com/DLR-RM/AugmentedAutoencoder) ⭐ 363 | 🐛 7 | 🌐 Python | 📅 2022-08-16 - RGB-based pipeline for object detection and 6D pose estimation.
* [jsk\_recognition](https://github.com/jsk-ros-pkg/jsk_recognition) ⭐ 290 | 🐛 137 | 🌐 C++ | 📅 2026-02-20 - A stack for the perception packages which are used in JSK lab.
* [SARosPerceptionKitti](https://github.com/appinho/SARosPerceptionKitti) ⭐ 250 | 🐛 2 | 🌐 Python | 📅 2022-03-17 - ROS package for the Perception (Sensor Processing, Detection, Tracking and Evaluation) of the KITTI Vision Benchmark Suite.
* [morefusion](https://github.com/wkentaro/morefusion) ⚠️ Archived - Multi-object Reasoning for 6D Pose Estimation from Volumetric Fusion.

### Machine Learning

* [ray](https://github.com/ray-project/ray) ⭐ 43,556 | 🐛 3,516 | 🌐 Python | 📅 2026-08-19 - A fast and simple framework for building and running distributed applications.
* [gym](https://github.com/openai/gym) ⚠️ Archived - A toolkit for developing and comparing reinforcement learning algorithms.
* [Netron](https://github.com/lutzroeder/Netron) ⭐ 33,367 | 🐛 16 | 🌐 JavaScript | 📅 2026-08-18 - Visualizer for neural network, deep learning and machine learning models.
* [fastai](https://github.com/fastai/fastai) ⭐ 28,115 | 🐛 266 | 🌐 Jupyter Notebook | 📅 2026-08-15 - The fastai library simplifies training fast and accurate neural nets using modern best practices.
* [mlflow](https://github.com/mlflow/mlflow) ⭐ 27,577 | 🐛 2,043 | 🌐 Python | 📅 2026-08-19 - A platform to streamline machine learning development, including tracking experiments, packaging code into reproducible runs, and sharing and deploying models.
* [MNN](https://github.com/alibaba/MNN) ⭐ 15,919 | 🐛 18 | 🌐 C++ | 📅 2026-08-19 - A blazing fast, lightweight deep learning framework, battle-tested by business-critical use cases in Alibaba.
* [DLIB](https://github.com/davisking/dlib) ⭐ 14,432 | 🐛 38 | 🌐 C++ | 📅 2026-08-11 - A toolkit for making real world machine learning and data analysis applications in C++.
* [Dopamine](https://github.com/google/dopamine) ⭐ 10,897 | 🐛 111 | 🌐 Jupyter Notebook | 📅 2026-03-24 - A research framework for fast prototyping of reinforcement learning algorithms.
* [tpot](https://github.com/EpistasisLab/tpot) ⭐ 10,051 | 🐛 312 | 🌐 Jupyter Notebook | 📅 2025-09-11 - A Python Automated Machine Learning tool that optimizes machine learning pipelines using genetic programming.
* [cnn-explainer](https://github.com/poloclub/cnn-explainer) ⭐ 9,020 | 🐛 7 | 🌐 JavaScript | 📅 2023-10-14 - Learning Convolutional Neural Networks with Interactive Visualization.
* [Trax](https://github.com/google/trax) ⚠️ Archived - A library for deep learning that focuses on sequence models and reinforcement learning.
* [deap](https://github.com/DEAP/deap) ⭐ 6,431 | 🐛 281 | 🌐 Python | 📅 2026-04-17 - Distributed Evolutionary Algorithms in Python.
* [leela-zero](https://github.com/leela-zero/leela-zero) ⭐ 5,581 | 🐛 374 | 🌐 C++ | 📅 2024-05-02 - This is a fairly faithful reimplementation of the system described in the Alpha Go Zero paper "Mastering the Game of Go without Human Knowledge".
* [ReAgent](https://github.com/facebookresearch/ReAgent) ⭐ 3,712 | 🐛 85 | 🌐 Python | 📅 2026-08-17 - An open source end-to-end platform for applied reinforcement learning (RL) developed and used at Facebook.
* [catalyst](https://github.com/catalyst-team/catalyst) ⭐ 3,381 | 🐛 5 | 🌐 Python | 📅 2026-07-08 - Was developed with a focus on reproducibility, fast experimentation and code/ideas reusing.
* [Tensorforce](https://github.com/tensorforce/tensorforce) ⭐ 3,306 | 🐛 44 | 🌐 Python | 📅 2026-07-14 - An open-source deep reinforcement learning framework, with an emphasis on modularized flexible library design and straightforward usability for applications in research and practice.
* [tf-agents](https://github.com/tensorflow/agents) ⭐ 3,025 | 🐛 212 | 🌐 Python | 📅 2026-01-16 - A reliable, scalable and easy to use TensorFlow library for Contextual Bandits and Reinforcement Learning.
* [Tensorflow Federated](https://github.com/tensorflow/federated) ⭐ 2,447 | 🐛 290 | 🌐 Python | 📅 2026-08-19 - TensorFlow Federated (TFF) is an open-source framework for machine learning and other computations on decentralized data.
* [finn](https://github.com/Xilinx/finn) ⭐ 1,042 | 🐛 113 | 🌐 Python | 📅 2026-08-19 - Fast, Scalable Quantized Neural Network Inference on FPGAs.
* [neuropod](https://github.com/uber/neuropod) ⭐ 943 | 🐛 53 | 🌐 C++ | 📅 2024-01-03 - Neuropod is a library that provides a uniform interface to run deep learning models from multiple frameworks in C++ and Python.
* [modelzoo](https://github.com/autowarefoundation/modelzoo) ⭐ 63 | 🐛 3 | 🌐 Python | 📅 2023-02-06 - A collection of machine-learned models for use in autonomous driving applications.
* [tensorflow\_ros\_cpp](https://github.com/tradr-project/tensorflow_ros_cpp) ⭐ 59 | 🐛 3 | 🌐 CMake | 📅 2022-06-08 - A ROS package that allows to do Tensorflow inference in C++ without the need to compile TF yourself.
* [nnstreamer-ros](https://github.com/nnstreamer/nnstreamer-ros) ⭐ 14 | 🐛 0 | 🌐 C++ | 📅 2020-12-02 - A set of Gstreamer plugins and ROS examples that allow Gstreamer developers to adopt neural network models easily and efficiently and neural network developers to manage neural network pipelines and their filters easily and efficiently.
* [Awesome-Mobile-Machine-Learning](https://github.com/fritzlabs/Awesome-Mobile-Machine-Learning) - A curated list of awesome mobile machine learning resources for iOS, Android, and edge devices.

### Parallel Processing

* [dask](https://github.com/dask/dask) ⭐ 13,891 | 🐛 1,310 | 🌐 Python | 📅 2026-08-17 - Parallel computing with task scheduling for Python.
* [TensorRT](https://github.com/NVIDIA/TensorRT) ⭐ 13,267 | 🐛 622 | 🌐 C++ | 📅 2026-08-17 - A C++ library for high performance inference on NVIDIA GPUs and deep learning accelerators.
* [cupy](https://github.com/cupy/cupy) ⭐ 12,258 | 🐛 703 | 🌐 Python | 📅 2026-08-18 - NumPy-like API accelerated with CUDA.
* [numba](https://github.com/numba/numba) ⭐ 11,124 | 🐛 1,799 | 🌐 Python | 📅 2026-08-19 - NumPy aware dynamic Python compiler using LLVM.
* [Thrust](https://github.com/thrust/thrust) ⚠️ Archived - A C++ parallel programming library which resembles the C++ Standard Library.
* [ArrayFire](https://github.com/arrayfire/arrayfire) ⭐ 4,900 | 🐛 318 | 🌐 C++ | 📅 2026-03-07 - A general purpose GPU library.
* [PYNQ](https://github.com/Xilinx/PYNQ) ⭐ 2,336 | 🐛 56 | 🌐 Jupyter Notebook | 📅 2026-08-14 - An open-source project from Xilinx that makes it easy to design embedded systems with Zynq All Programmable Systems on Chips.
* [libcudacxx](https://github.com/NVIDIA/libcudacxx) ⚠️ Archived - Provides a heterogeneous implementation of the C++ Standard Library that can be used in and between CPU and GPU code.
* [VexCL](https://github.com/ddemidov/vexcl) ⭐ 721 | 🐛 31 | 🌐 C++ | 📅 2025-07-19 - VexCL is a C++ vector expression template library for OpenCL/CUDA/OpenMP.
* [OpenMP](https://www.openmp.org/) - An application programming interface that supports multi-platform shared memory multiprocessing programming in C, C++, and Fortran.

### Image Processing

* [detectron2](https://github.com/facebookresearch/detectron2) ⭐ 34,674 | 🐛 587 | 🌐 Python | 📅 2026-08-19 - A next-generation research platform for object detection and segmentation.
* [EasyOCR](https://github.com/JaidedAI/EasyOCR) ⭐ 29,916 | 🐛 530 | 🌐 Python | 📅 2025-12-05 - Ready-to-use Optical character recognition (OCR) with 40+ languages supported including Chinese, Japanese, Korean and Thai.
* [imgaug](https://github.com/aleju/imgaug) ⭐ 14,739 | 🐛 311 | 🌐 Python | 📅 2024-07-30 - Image augmentation for machine learning experiments.
* [meshroom](https://github.com/alicevision/meshroom) ⭐ 12,907 | 🐛 516 | 🌐 Python | 📅 2026-08-19 - Meshroom is a free, open-source 3D Reconstruction Software based on the AliceVision Photogrammetric Computer Vision framework.
* [libvips](https://github.com/libvips/libvips) ⭐ 11,578 | 🐛 82 | 🌐 C | 📅 2026-08-18 - A fast image processing library with low memory needs.
* [satellite-image-deep-learning](https://github.com/robmarkcole/satellite-image-deep-learning) ⭐ 10,233 | 🐛 0 | 📅 2026-08-02 - Resources for deep learning with satellite & aerial imagery.
* [fawkes](https://github.com/Shawn-Shan/fawkes) ⭐ 5,588 | 🐛 43 | 🌐 Python | 📅 2023-08-02 - Privacy preserving tool against facial recognition systems.
* [yolact](https://github.com/dbolya/yolact) ⭐ 5,241 | 🐛 415 | 🌐 Python | 📅 2025-09-09 - A simple, fully convolutional model for real-time instance segmentation.
* [pysot](https://github.com/STVIR/pysot) ⭐ 4,600 | 🐛 59 | 🌐 Python | 📅 2025-06-22 - The goal of PySOT is to provide a high-quality, high-performance codebase for visual tracking research.
* [pytracking](https://github.com/visionml/pytracking) ⭐ 3,515 | 🐛 81 | 🌐 Python | 📅 2024-08-08 - A general python framework for visual object tracking and video object segmentation, based on PyTorch.
* [AliceVision](https://github.com/alicevision/AliceVision) ⭐ 3,480 | 🐛 41 | 🌐 C++ | 📅 2026-08-19 - A Photogrammetric Computer Vision Framework which provides a 3D Reconstruction and Camera Tracking algorithms.
* [flownet2-pytorch](https://github.com/NVIDIA/flownet2-pytorch) ⭐ 3,289 | 🐛 167 | 🌐 Python | 📅 2026-03-30 - Pytorch implementation of FlowNet 2.0: Evolution of Optical Flow Estimation with Deep Networks.
* [simpledet](https://github.com/tusimple/simpledet) ⭐ 3,084 | 🐛 44 | 🌐 Python | 📅 2021-09-23 - A Simple and Versatile Framework for Object Detection and Instance Recognition.
* [darknet\_ros](https://github.com/leggedrobotics/darknet_ros) ⭐ 2,440 | 🐛 166 | 🌐 C++ | 📅 2024-07-19 - YOLO ROS: Real-Time Object Detection for ROS.
* [Simd](https://github.com/ermig1979/Simd) ⭐ 2,265 | 🐛 28 | 🌐 C++ | 📅 2026-08-19 - C++ image processing and machine learning library with using of SIMD: SSE, SSE2, SSE3, SSSE3, SSE4.1, SSE4.2, AVX, AVX2, AVX-512, VMX(Altivec) and VSX(Power7), NEON for ARM.
* [robosat](https://github.com/mapbox/robosat) ⭐ 2,064 | 🐛 58 | 🌐 Python | 📅 2026-06-29 - Semantic segmentation on aerial and satellite imagery.
* [SfMLearner](https://github.com/tinghuiz/SfMLearner) ⭐ 2,016 | 🐛 48 | 🌐 Jupyter Notebook | 📅 2021-10-26 - An unsupervised learning framework for depth and ego-motion estimation.
* [AB3DMOT](https://github.com/xinshuoweng/AB3DMOT) ⭐ 1,845 | 🐛 24 | 🌐 Python | 📅 2024-04-03 - This work proposes a simple yet accurate real-time baseline 3D multi-object tracking system.
* [opendatacam](https://github.com/opendatacam/opendatacam) ⭐ 1,725 | 🐛 62 | 🌐 JavaScript | 📅 2026-04-23 - Only saves surveyed meta-data, in particular the path an object moved or number of counted objects at a certain point.
* [big\_transfer](https://github.com/google-research/big_transfer) ⚠️ Archived - Model for General Visual Representation Learning created by Google Research.
* [TorchSeg](https://github.com/ycszen/TorchSeg) ⭐ 1,410 | 🐛 41 | 🌐 Python | 📅 2020-03-11 - This project aims at providing a fast, modular reference implementation for semantic segmentation models using PyTorch.
* [CV-pretrained-model](https://github.com/balavenkatesh3322/CV-pretrained-model) ⭐ 1,365 | 🐛 2 | 📅 2021-03-03 - A collection of computer vision pre-trained models.
* [packnet-sfm](https://github.com/TRI-ML/packnet-sfm) ⭐ 1,275 | 🐛 80 | 🌐 Python | 📅 2023-07-16 - Official PyTorch implementation of self-supervised monocular depth estimation methods invented by the ML Team at Toyota Research Institute (TRI).
* [hyperpose](https://github.com/tensorlayer/hyperpose) ⭐ 1,264 | 🐛 33 | 🌐 Python | 📅 2023-03-25 - HyperPose: A Flexible Library for Real-time Human Pose Estimation.
* [eo-learn](https://github.com/sentinel-hub/eo-learn) ⭐ 1,245 | 🐛 7 | 🌐 Python | 📅 2026-01-15 - A collection of open source Python packages that have been developed to seamlessly access and process spatio-temporal image sequences acquired by any satellite fleet in a timely and automatic manner.
* [satpy](https://github.com/pytroll/satpy) ⭐ 1,204 | 🐛 566 | 🌐 Python | 📅 2026-08-18 - A python library for reading and manipulating meteorological remote sensing data and writing it to various image and data file formats.
* [deep\_object\_pose](https://github.com/NVlabs/Deep_Object_Pose) ⭐ 1,176 | 🐛 87 | 🌐 Python | 📅 2025-08-06 - Deep Object Pose Estimation.
* [DetectAndTrack](https://github.com/facebookresearch/DetectAndTrack) ⚠️ Archived - Detect-and-Track: Efficient Pose.
* [ros\_deep\_learning](https://github.com/dusty-nv/ros_deep_learning) ⭐ 978 | 🐛 93 | 🌐 C++ | 📅 2024-07-13 - Deep learning inference nodes for ROS with support for NVIDIA Jetson TX1/TX2/Xavier and TensorRT.
* [image\_pipeline](https://github.com/ros-perception/image_pipeline) ⭐ 960 | 🐛 60 | 🌐 C++ | 📅 2026-07-20 - Fills the gap between getting raw images from a camera driver and higher-level vision processing.
* [Cam2BEV](https://github.com/ika-rwth-aachen/Cam2BEV) ⭐ 790 | 🐛 0 | 🌐 Python | 📅 2025-05-17 - TensorFlow Implementation for Computing a Semantically Segmented Bird's Eye View (BEV) Image Given the Images of Multiple Vehicle-Mounted Cameras.
* [Kimera-Semantics](https://github.com/MIT-SPARK/Kimera-Semantics) ⭐ 748 | 🐛 29 | 🌐 C++ | 📅 2023-12-07 - Real-Time 3D Semantic Reconstruction from 2D data.
* [semantic\_slam](https://github.com/floatlazer/semantic_slam) ⭐ 716 | 🐛 44 | 🌐 C++ | 📅 2019-05-16 - Real time semantic slam in ROS with a hand held RGB-D camera.
* [3d-vehicle-tracking](https://github.com/ucbdrive/3d-vehicle-tracking) ⭐ 683 | 🐛 10 | 🌐 Python | 📅 2022-12-03 - Official implementation of Joint Monocular 3D Vehicle Detection and Tracking.
* [vision\_opencv](https://github.com/ros-perception/vision_opencv) ⭐ 666 | 🐛 68 | 🌐 C++ | 📅 2025-12-29 - Packages for interfacing ROS with OpenCV, a library of programming functions for real time computer vision.
* [LEDNet](https://github.com/xiaoyufenfei/LEDNet) ⭐ 522 | 🐛 12 | 🌐 Python | 📅 2020-12-05 - A Lightweight Encoder-Decoder Network for Real-time Semantic Segmentation.
* [find-object](https://github.com/introlab/find-object) ⭐ 480 | 🐛 77 | 🌐 C++ | 📅 2025-06-02 - Simple Qt interface to try OpenCV implementations of SIFT, SURF, FAST, BRIEF and other feature detectors and descriptors.
* [apriltag\_ros](https://github.com/AprilRobotics/apriltag_ros) ⭐ 461 | 🐛 35 | 🌐 C++ | 📅 2024-06-23 - A ROS wrapper of the AprilTag 3 visual fiducial detector.
* [monoloco](https://github.com/vita-epfl/monoloco) ⭐ 460 | 🐛 13 | 🌐 Python | 📅 2022-05-24 - Official implementation of "MonoLoco: Monocular 3D Pedestrian Localization and Uncertainty Estimation" in PyTorch.
* [anonymizer](https://github.com/understand-ai/anonymizer) ⚠️ Archived - An anonymizer to obfuscate faces and license plates.
* [vision\_visp](https://github.com/lagadic/vision_visp) ⭐ 225 | 🐛 45 | 🌐 C++ | 📅 2026-03-04 - Wraps the ViSP moving edge tracker provided by the ViSP visual servoing library into a ROS package.
* [ros2\_openvino\_toolkit](https://github.com/intel/ros2_openvino_toolkit) ⭐ 188 | 🐛 24 | 🌐 C++ | 📅 2026-06-10 -  Provides a ROS-adaptered runtime framework of neural network which quickly deploys applications and solutions for vision inference.
* [ros\_ncnn](https://github.com/nilseuropa/ros_ncnn) ⭐ 65 | 🐛 1 | 🌐 C++ | 📅 2021-03-14 - YOLACT / YOLO *( among other things )* on NCNN inference engine for ROS.
* [kitti\_scan\_unfolding](https://github.com/ltriess/kitti_scan_unfolding) ⭐ 16 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2025-06-20 - We propose KITTI scan unfolding in our paper Scan-based Semantic Segmentation of LiDAR Point Clouds: An Experimental Study.
* [gstreamer](https://gstreamer.freedesktop.org/) - A pipeline-based multimedia framework that links together a wide variety of media processing systems to complete complex workflows.
* [tf-pose-estimation](https://github.com/ildoonet/tf-pose-estimation) - Deep Pose Estimation implemented using Tensorflow with Custom Architectures for fast inference.
* [OpenVX](https://www.khronos.org/openvx/) -  Enables performance and power-optimized computer vision processing, especially important in embedded and real-time use cases.
* [Poly-YOLO](https://gitlab.com/irafm-ai/poly-yolo) - Builds on the original ideas of YOLOv3 and removes two of its weaknesses: a large amount of rewritten labels and inefficient distribution of anchors.

### Radar Processing

* [pyroSAR](https://github.com/johntruckenbrodt/pyroSAR) ⭐ 611 | 🐛 46 | 🌐 Python | 📅 2026-08-11 - Framework for large-scale SAR satellite data processing.
* [CameraRadarFusionNet](https://github.com/TUMFTM/CameraRadarFusionNet) ⭐ 451 | 🐛 30 | 🌐 Python | 📅 2026-08-09 - TUM Roborace Team Software Stack - Path tracking control, velocity control, curvature control and state estimation.

### Lidar and Point Cloud Processing

* [open3d](https://github.com/intel-isl/Open3D) ⭐ 13,896 | 🐛 1,345 | 🌐 C++ | 📅 2026-08-19 - Open3D: A Modern Library for 3D Data Processing.
* [Draco](https://github.com/google/draco) ⭐ 7,444 | 🐛 171 | 🌐 C++ | 📅 2026-08-18 - A library for compressing and decompressing 3D geometric meshes and point clouds.
* [mmdetection3d](https://github.com/open-mmlab/mmdetection3d) ⭐ 6,512 | 🐛 654 | 🌐 Python | 📅 2024-07-10 - Next-generation platform for general 3D object detection.
* [PCDet](https://github.com/sshaoshuai/PCDet) ⭐ 5,684 | 🐛 30 | 🌐 Python | 📅 2025-10-08 - A general PyTorch-based codebase for 3D object detection from point cloud.
* [OpenPCDet](https://github.com/open-mmlab/OpenPCDet) ⭐ 5,684 | 🐛 30 | 🌐 Python | 📅 2025-10-08 - A Toolbox for LiDAR-based 3D Object Detection.
* [kaolin](https://github.com/NVIDIAGameWorks/kaolin) ⭐ 5,158 | 🐛 30 | 🌐 Python | 📅 2026-08-14 - A PyTorch Library for Accelerating 3D Deep Learning Research.
* [grid\_map](https://github.com/ANYbotics/grid_map) ⭐ 3,215 | 🐛 164 | 🌐 C++ | 📅 2026-01-13 - Universal grid map library for mobile robotic mapping.
* [octomap](https://github.com/OctoMap/octomap) ⭐ 2,359 | 🐛 44 | 🌐 C++ | 📅 2026-08-02 - An Efficient Probabilistic 3D Mapping Framework Based on Octrees.
* [KISS-ICP](https://github.com/PRBonn/kiss-icp) ⭐ 2,298 | 🐛 18 | 🌐 C++ | 📅 2026-06-09 - A LiDAR Odometry pipeline that just works on most of the cases without tunning any parameter.
* [python-pcl](https://github.com/strawlab/python-pcl) ⚠️ Archived - Python bindings to the pointcloud library.
* [elevation\_mapping](https://github.com/ANYbotics/elevation_mapping) ⭐ 1,850 | 🐛 101 | 🌐 C++ | 📅 2024-11-04 - Robot-centric elevation mapping for rough terrain navigation.
* [libpointmatcher](https://github.com/ethz-asl/libpointmatcher) ⭐ 1,827 | 🐛 100 | 🌐 C++ | 📅 2025-10-29 - An "Iterative Closest Point" library for 2-D/3-D mapping in Robotics.
* [Votenet](https://github.com/facebookresearch/votenet) ⚠️ Archived - Deep Hough Voting for 3D Object Detection in Point Clouds.
* [fast\_gicp](https://github.com/SMRT-AIST/fast_gicp) ⭐ 1,682 | 🐛 76 | 🌐 C++ | 📅 2025-04-24 - A collection of GICP-based fast point cloud registration algorithms.
* [RandLA-Net](https://github.com/QingyongHu/RandLA-Net) ⭐ 1,559 | 🐛 194 | 🌐 Python | 📅 2023-07-11 - Efficient Semantic Segmentation of Large-Scale Point Clouds.
* [Det3D](https://github.com/poodarchu/Det3D) ⭐ 1,559 | 🐛 20 | 🌐 Python | 📅 2023-12-19 - A first 3D Object Detection toolbox which provides off the box implementations of many 3D object detection algorithms such as PointPillars, SECOND, PIXOR.
* [PointCNN](https://github.com/yangyanli/PointCNN) ⭐ 1,432 | 🐛 61 | 🌐 Python | 📅 2026-03-12 - A simple and general framework for feature learning from point clouds.
* [PDAL](https://github.com/PDAL/PDAL) ⭐ 1,403 | 🐛 133 | 🌐 C++ | 📅 2026-08-18 - A C++ BSD library for translating and manipulating point cloud data.
* [depth\_clustering](https://github.com/PRBonn/depth_clustering) ⭐ 1,312 | 🐛 8 | 🌐 C++ | 📅 2021-11-11 - Fast and robust clustering of point clouds generated with a Velodyne sensor.
* [cilantro](https://github.com/kzampog/cilantro) ⭐ 1,135 | 🐛 19 | 🌐 C++ | 📅 2025-06-23 - A lean C++ library for working with point cloud data.
* [Super-Fast-Accurate-3D-Object-Detection](https://github.com/maudzung/Super-Fast-Accurate-3D-Object-Detection) ⭐ 1,128 | 🐛 23 | 🌐 Python | 📅 2023-09-17 - Super Fast and Accurate 3D Object Detection based on 3D LiDAR Point Clouds (The PyTorch implementation).
* [LAStools](https://github.com/LAStools/LAStools) ⭐ 1,064 | 🐛 59 | 🌐 C++ | 📅 2026-08-10 - Award-winning software for efficient LiDAR processing.
* [Cupoch](https://github.com/neka-nat/cupoch) ⭐ 1,062 | 🐛 24 | 🌐 C++ | 📅 2026-06-25 -  A library that implements rapid 3D data processing and robotics computation using CUDA.
* [lidar-bonnetal](https://github.com/PRBonn/lidar-bonnetal) ⚠️ Archived - Semantic and Instance Segmentation of LiDAR point clouds for autonomous driving.
* [ndt\_omp](https://github.com/koide3/ndt_omp) ⭐ 855 | 🐛 32 | 🌐 C++ | 📅 2024-08-31 - Multi-threaded and SSE friendly NDT algorithm.
* [spatio\_temporal\_voxel\_layer](https://github.com/SteveMacenski/spatio_temporal_voxel_layer) ⭐ 854 | 🐛 15 | 🌐 C++ | 📅 2026-08-05 - A new voxel layer leveraging modern 3D graphics tools to modernize navigation environmental representations.
* [PolyFit](https://github.com/LiangliangNan/PolyFit) ⭐ 828 | 🐛 1 | 🌐 C++ | 📅 2025-04-16 - Polygonal Surface Reconstruction from Point Clouds.
* [PotreeConverter](https://github.com/potree/PotreeConverter) ⭐ 815 | 🐛 185 | 🌐 JavaScript | 📅 2026-06-22 - Builds a potree octree from las, laz, binary ply, xyz or ptx files.
* [linefit\_ground\_segmentation](https://github.com/lorenwel/linefit_ground_segmentation) ⭐ 808 | 🐛 5 | 🌐 C++ | 📅 2024-07-26 - Implementation of the ground segmentation algorithm.
* [superpoint\_graph](https://github.com/loicland/superpoint_graph) ⭐ 801 | 🐛 16 | 🌐 Python | 📅 2023-07-19 - Large-scale Point Cloud Semantic Segmentation with Superpoint Graphs.
* [gpd](https://github.com/atenpas/gpd) ⭐ 767 | 🐛 63 | 🌐 C++ | 📅 2022-01-31 - Takes a point cloud as input and produces pose estimates of viable grasps as output.
* [OverlapNet](https://github.com/PRBonn/OverlapNet) ⭐ 734 | 🐛 8 | 🌐 Python | 📅 2023-03-24 - A modified Siamese Network that predicts the overlap and relative yaw angle of a pair of range images generated by 3D LiDAR scans.
* [cuda-pcl](https://github.com/NVIDIA-AI-IOT/cuda-pcl) ⭐ 700 | 🐛 64 | 🌐 C++ | 📅 2024-05-16 - Accelerating Lidar for Robotics with NVIDIA CUDA-based PCL.
* [Removert](https://github.com/irapkaist/removert) ⭐ 646 | 🐛 18 | 🌐 C++ | 📅 2026-04-25 - Remove then revert. Static map construction in the wild and dynamic points removing tool by constructing a static map.
* [CSF](https://github.com/jianboqi/CSF) ⭐ 642 | 🐛 16 | 🌐 C++ | 📅 2025-08-13 - LiDAR point cloud ground filtering / segmentation (bare earth extraction) method based on cloth simulation.
* [pptk](https://github.com/heremaps/pptk) ⭐ 634 | 🐛 59 | 🌐 C++ | 📅 2020-09-17 - Point Processing Toolkit from HEREMaps.
* [pointcloud\_to\_laserscan](https://github.com/ros-perception/pointcloud_to_laserscan) ⭐ 596 | 🐛 10 | 🌐 C++ | 📅 2025-08-28 - Converts a 3D Point Cloud into a 2D laser scan.
* [SqueezeSeg](https://github.com/BichenWuUCB/SqueezeSeg) ⭐ 575 | 🐛 43 | 🌐 Python | 📅 2019-05-22 - Implementation of SqueezeSeg, convolutional neural networks for LiDAR point clout segmentation.
* [CamVox](https://github.com/ISEE-Technology/CamVox) ⭐ 566 | 🐛 17 | 🌐 C++ | 📅 2021-12-02 - A low-cost SLAM system based on camera and Livox lidar.
* [Go-ICP](https://github.com/yangjiaolong/Go-ICP) ⭐ 506 | 🐛 11 | 🌐 C++ | 📅 2019-06-02 - Implementation of the Go-ICP algorithm for globally optimal 3D pointset registration.
* [SA-SSD](https://github.com/skyhehe123/SA-SSD) ⭐ 495 | 🐛 57 | 🌐 Python | 📅 2020-08-05 - Structure Aware Single-stage 3D Object Detection from Point Cloud.
* [SalsaNext](https://github.com/TiagoCortinhal/SalsaNext) ⭐ 470 | 🐛 13 | 🌐 Python | 📅 2024-11-20 - Uncertainty-aware Semantic Segmentation of LiDAR Point Clouds for Autonomous Driving.
* [laser\_line\_extraction](https://github.com/kam3k/laser_line_extraction) ⭐ 432 | 🐛 11 | 🌐 C++ | 📅 2022-08-15 - A ROS packages that extracts line segments from LaserScan messages.
* [PolarSeg](https://github.com/edwardzhou130/PolarSeg) ⭐ 419 | 🐛 27 | 🌐 Python | 📅 2021-05-19 - An Improved Grid Representation for Online LiDAR Point Clouds Semantic Segmentation.
* [segmenters\_lib](https://github.com/LidarPerception/segmenters_lib) ⭐ 418 | 🐛 6 | 🌐 C++ | 📅 2022-10-08 - The LiDAR segmenters library, for segmentation-based detection.
* [rangenet\_lib](https://github.com/PRBonn/rangenet_lib) ⭐ 359 | 🐛 13 | 🌐 C++ | 📅 2022-07-11 - Contains simple usage explanations of how the RangeNet++ inference works with the TensorRT and C++ interface.
* [urban\_road\_filter](https://github.com/jkk-research/urban_road_filter) ⭐ 356 | 🐛 4 | 🌐 C++ | 📅 2026-07-06 - Real-time LIDAR-based Urban Road and Sidewalk detection for Autonomous Vehicles.
* [traversability\_mapping](https://github.com/TixiaoShan/traversability_mapping) ⭐ 341 | 🐛 12 | 🌐 C++ | 📅 2020-08-13 - Takes in point cloud from a Velodyne VLP-16 Lidar and outputs a traversability map for autonomous navigation in real-time.
* [torch-points3d](https://github.com/nicolas-chaulet/torch-points3d) ⭐ 268 | 🐛 0 | 📅 2021-12-10 - Pytorch framework for doing deep learning on point clouds.
* [lidar\_super\_resolution](https://github.com/RobustFieldAutonomyLab/lidar_super_resolution) ⭐ 197 | 🐛 8 | 🌐 Python | 📅 2021-02-02 - Simulation-based Lidar Super-resolution for Ground Vehicles.
* [point\_cloud\_io](https://github.com/ANYbotics/point_cloud_io) ⭐ 192 | 🐛 0 | 🌐 C++ | 📅 2024-08-23 - ROS nodes to read and write point clouds from and to files (e.g. ply, vtk).
* [mp2p\_icp](https://github.com/MOLAorg/mp2p_icp) ⭐ 188 | 🐛 2 | 🌐 C++ | 📅 2026-08-15 - A repertory of multi primitive-to-primitive (MP2P) ICP algorithms in C++.
* [MotionNet](https://github.com/pxiangwu/MotionNet) ⭐ 175 | 🐛 0 | 📅 2020-06-04 - Joint Perception and Motion Prediction for Autonomous Driving Based on Bird's Eye View Maps.
* [lidar\_undistortion](https://github.com/ethz-asl/lidar_undistortion) ⭐ 160 | 🐛 2 | 🌐 C++ | 📅 2023-04-17 - Provides lidar motion undistortion based on an external 6DoF pose estimation input.
* [robot\_body\_filter](https://github.com/peci1/robot_body_filter) ⭐ 104 | 🐛 7 | 🌐 C++ | 📅 2026-04-06 - A highly configurable LaserScan/PointCloud2 filter that allows to dynamically remove the 3D body of the robot from the measurements.
* [gpu-voxels](https://www.gpu-voxels.org/) - GPU-Voxels is a CUDA based library which allows high resolution volumetric collision detection between animated 3D models and live pointclouds from 3D sensors of all kinds.

## Localization and State Estimation

* [Kalman-and-Bayesian-Filters-in-Python](https://github.com/rlabbe/Kalman-and-Bayesian-Filters-in-Python) ⭐ 19,211 | 🐛 143 | 🌐 Jupyter Notebook | 📅 2024-08-07 - Kalman Filter book using Jupyter Notebook.
* [evo](https://github.com/MichaelGrupp/evo) ⭐ 4,300 | 🐛 8 | 🌐 Python | 📅 2026-08-14 - Python package for the evaluation of odometry and SLAM.
* [PROJ](https://github.com/OSGeo/PROJ) ⭐ 2,006 | 🐛 99 | 🌐 C++ | 📅 2026-08-19 - Cartographic Projections and Coordinate Transformations Library.
* [robot\_localization](https://github.com/cra-ros-pkg/robot_localization) ⭐ 1,942 | 🐛 90 | 🌐 C++ | 📅 2026-07-16 - A package of nonlinear state estimation nodes.
* [rpg\_trajectory\_evaluation](https://github.com/uzh-rpg/rpg_trajectory_evaluation) ⭐ 1,211 | 🐛 39 | 🌐 Python | 📅 2023-03-30 -  Implements common used trajectory evaluation methods for visual(-inertial) odometry.
* [imu\_tools](https://github.com/ccny-ros-pkg/imu_tools) ⭐ 1,123 | 🐛 25 | 🌐 C++ | 📅 2026-06-15 - IMU-related filters and visualizers.
* [ai-imu-dr](https://github.com/mbrossar/ai-imu-dr) ⭐ 995 | 🐛 39 | 🌐 Python | 📅 2025-01-08 - Contains the code of our novel accurate method for dead reckoning of wheeled vehicles based only on an IMU.
* [RTKLIB](https://github.com/rtklibexplorer/RTKLIB) ⭐ 962 | 🐛 93 | 🌐 C | 📅 2026-08-06 - A version of RTKLIB optimized for single and dual frequency low cost GPS receivers, especially u-blox receivers.
* [dynamic\_robot\_localization](https://github.com/carlosmccosta/dynamic_robot_localization) ⭐ 899 | 🐛 23 | 🌐 C++ | 📅 2024-07-25 - A ROS package that offers 3 DoF and 6 DoF localization using PCL and allows dynamic map update using OctoMap.
* [fuse](https://github.com/locusrobotics/fuse) ⭐ 874 | 🐛 49 | 🌐 C++ | 📅 2026-08-15 - General architecture for performing sensor fusion live on a robot.
* [eagleye](https://github.com/MapIV/eagleye) ⭐ 771 | 🐛 24 | 🌐 C++ | 📅 2026-04-06 -  An open-source software for vehicle localization utilizing GNSS and IMU.
* [mcl\_3dl](https://github.com/at-wat/mcl_3dl) ⭐ 600 | 🐛 34 | 🌐 C++ | 📅 2025-12-22 - A ROS node to perform a probabilistic 3-D/6-DOF localization system for mobile robots with 3-D LIDAR(s).
* [python-sgp4](https://github.com/brandon-rhodes/python-sgp4) ⭐ 469 | 🐛 7 | 🌐 Python | 📅 2026-07-12 - Python version of the SGP4 satellite position library.
* [pymap3d](https://github.com/geospace-code/pymap3d) ⭐ 442 | 🐛 6 | 🌐 Python | 📅 2026-06-22 - Pure-Python (Numpy optional) 3D coordinate conversions for geospace ecef enu eci.
* [se2lam](https://github.com/izhengfan/se2lam) ⭐ 410 | 🐛 3 | 🌐 C++ | 📅 2024-06-04 - On-SE(2) Localization and Mapping for Ground Vehicles by Fusing Odometry and Vision.
* [libRSF](https://github.com/TUC-ProAut/libRSF) ⭐ 336 | 🐛 2 | 🌐 C++ | 📅 2026-04-06 - A robust sensor fusion library for online localization.
* [mmWave-localization-learning](https://github.com/gante/mmWave-localization-learning) ⭐ 132 | 🐛 5 | 🌐 Python | 📅 2024-07-30 - ML-based positioning method from mmWave transmissions - with high accuracy and energy efficiency.
* [GeographicLib](https://github.com/Sciumo/GeographicLib) ⭐ 39 | 🐛 0 | 🌐 C++ | 📅 2015-08-05 - A C++ library for geographic projections.
* [ntripbrowser](https://github.com/emlid/ntripbrowser) ⭐ 32 | 🐛 6 | 🌐 Python | 📅 2025-07-21 - A Python API for browsing NTRIP (Networked Transport of RTCM via Internet Protocol).
* [gLAB](https://gage.upc.edu/gLAB/) - Performs precise modeling of GNSS observables (pseudorange and carrier phase) at the centimetre level, allowing standalone GPS positioning, PPP, SBAS and DGNSS.

## Simultaneous Localization and Mapping

### Lidar

* [LIO\_SAM](https://github.com/TixiaoShan/LIO-SAM) ⭐ 4,889 | 🐛 183 | 🌐 C++ | 📅 2025-02-14 - Tightly-coupled Lidar Inertial Odometry via Smoothing and Mapping.
* [pyslam](https://github.com/luigifreda/pyslam) ⭐ 3,399 | 🐛 3 | 🌐 Python | 📅 2026-08-01 - Contains a monocular Visual Odometry (VO) pipeline in Python.
* [maplab](https://github.com/ethz-asl/maplab) ⭐ 2,866 | 🐛 124 | 🌐 C++ | 📅 2024-05-31 - An open visual-inertial mapping framework.
* [LeGO-LOAM](https://github.com/RobustFieldAutonomyLab/LeGO-LOAM) ⭐ 2,753 | 🐛 40 | 🌐 C++ | 📅 2024-08-17 - Lightweight and Ground-Optimized Lidar Odometry and Mapping on Variable Terrain.
* [slam\_toolbox](https://github.com/SteveMacenski/slam_toolbox) ⭐ 2,605 | 🐛 48 | 🌐 C++ | 📅 2026-08-17 - Slam Toolbox for lifelong mapping and localization in potentially massive maps with ROS .
* [A-LOAM](https://github.com/HKUST-Aerial-Robotics/A-LOAM) ⭐ 2,438 | 🐛 52 | 🌐 C++ | 📅 2023-10-19 - Advanced implementation of LOAM.
* [hdl\_graph\_slam](https://github.com/koide3/hdl_graph_slam) ⭐ 2,324 | 🐛 126 | 🌐 C++ | 📅 2024-07-16 - An open source ROS package for real-time 6DOF SLAM using a 3D LIDAR.
* [KISS-ICP](https://github.com/PRBonn/kiss-icp) ⭐ 2,298 | 🐛 18 | 🌐 C++ | 📅 2026-06-09 - A LiDAR Odometry pipeline that just works on most of the cases without tunning any parameter.
* [cartographer\_ros](https://github.com/googlecartographer/cartographer_ros) ⭐ 1,851 | 🐛 289 | 🌐 C++ | 📅 2024-03-10 - Provides ROS integration for Cartographer.
* [loam\_velodyne](https://github.com/laboshinl/loam_velodyne) ⭐ 1,758 | 🐛 108 | 🌐 C++ | 📅 2019-06-18 - Laser Odometry and Mapping (Loam) is a realtime method for state estimation and mapping using a 3D lidar.
* [loam\_livox](https://github.com/hku-mars/loam_livox) ⭐ 1,618 | 🐛 71 | 🌐 C++ | 📅 2020-02-24 - A robust LiDAR Odometry and Mapping (LOAM) package for Livox-LiDAR.
* [Fast LOAM](https://github.com/wh200720041/floam) ⭐ 1,143 | 🐛 43 | 🌐 C++ | 📅 2024-07-30 - Fast and Optimized Lidar Odometry And Mapping.
* [lio-mapping](https://github.com/hyye/lio-mapping) ⭐ 1,027 | 🐛 35 | 🌐 C++ | 📅 2020-02-13 - Implementation of Tightly Coupled 3D Lidar Inertial Odometry and Mapping (LIO-mapping).
* [semantic\_suma](https://github.com/PRBonn/semantic_suma/) ⭐ 1,014 | 🐛 5 | 🌐 C++ | 📅 2024-03-12 - Semantic Mapping using Surfel Mapping and Semantic Segmentation.
* [mola](https://github.com/MOLAorg/mola) ⭐ 992 | 🐛 34 | 🌐 C++ | 📅 2026-08-19 - A Modular System for Localization and Mapping.
* [interactive\_slam](https://github.com/SMRT-AIST/interactive_slam) ⭐ 967 | 🐛 34 | 🌐 C++ | 📅 2024-08-04 -  In contrast to existing automatic SLAM packages, we with minimal human effort.
* [M-LOAM](https://github.com/gogojjh/M-LOAM) ⭐ 518 | 🐛 10 | 🌐 C++ | 📅 2025-02-06 - Robust Odometry and Mapping for Multi-LiDAR Systems with Online Extrinsic Calibration.
* [LaMa](https://github.com/iris-ua/iris_lama) ⭐ 351 | 🐛 7 | 🌐 C++ | 📅 2024-03-11 - LaMa is a C++11 software library for robotic localization and mapping.
* [StaticMapping](https://github.com/EdwardLiuyc/StaticMapping) ⭐ 346 | 🐛 1 | 🌐 C++ | 📅 2022-11-23 - Use LiDAR to map the static world.
* [DH3D](https://github.com/JuanDuGit/DH3D) ⭐ 160 | 🐛 0 | 🌐 Python | 📅 2020-11-11 - Deep Hierarchical 3D Descriptors for Robust Large-Scale 6DOF Relocalization.
* [horizon\_highway\_slam](https://github.com/Livox-SDK/horizon_highway_slam) ⭐ 154 | 🐛 5 | 🌐 C++ | 📅 2021-06-01 - A robust, low drift, and real time highway SLAM package suitable for Livox Horizon lidar.
* [Kitware SLAM](https://gitlab.kitware.com/keu-computervision/slam/) -  LiDAR-only visual SLAM developped by Kitware, as well as ROS and ParaView wrappings for easier use.
* [Scan Context](https://github.com/irapkaist/scancontext) - Global LiDAR descriptor for place recognition and long-term localization.

### Visual

* [ORB\_SLAM3](https://github.com/UZ-SLAMLab/ORB_SLAM3) ⭐ 8,965 | 🐛 572 | 🌐 C++ | 📅 2024-07-24 - ORB-SLAM3: An Accurate Open-Source Library for Visual, Visual-Inertial and Multi-Map SLAM.
* [VINS-Fusion](https://github.com/HKUST-Aerial-Robotics/VINS-Fusion) ⭐ 4,674 | 🐛 212 | 🌐 C++ | 📅 2024-05-23 - A Robust and Versatile Multi-Sensor Visual-Inertial State Estimator.
* [hloc](https://github.com/cvg/Hierarchical-Localization) ⭐ 4,183 | 🐛 162 | 🌐 Python | 📅 2025-12-10 - A modular toolbox for state-of-the-art 6-DoF visual localization. It implements Hierarchical Localization, leveraging image retrieval and feature matching, and is fast, accurate, and scalable.
* [open\_vins](https://github.com/rpng/open_vins) ⭐ 3,049 | 🐛 74 | 🌐 C++ | 📅 2025-11-30 - An open source platform for visual-inertial navigation research.
* [openvslam](https://github.com/xdspacelab/openvslam) ⚠️ Archived - OpenVSLAM: A Versatile Visual SLAM Framework.
* [LSD-SLAM](https://github.com/tum-vision/lsd_slam) ⭐ 2,720 | 🐛 240 | 🌐 C++ | 📅 2023-03-23 - Large-Scale Direct Monocular SLAM is a real-time monocular SLAM.
* [dso](https://github.com/JakobEngel/dso/) ⭐ 2,451 | 🐛 138 | 🌐 C++ | 📅 2024-02-23 - Direct Sparse Odometry.
* [Kimera](https://github.com/MIT-SPARK/Kimera) ⭐ 2,118 | 🐛 2 | 📅 2021-01-30 - A C++ library for real-time metric-semantic simultaneous localization and mapping, which uses camera images and inertial data to build a semantically annotated 3D mesh of the environment.
* [Atlas](https://github.com/magicleap/Atlas) ⭐ 1,858 | 🐛 53 | 🌐 Python | 📅 2022-04-06 - End-to-End 3D Scene Reconstruction from Posed Images.
* [gradslam](https://github.com/gradslam/gradslam) ⭐ 1,423 | 🐛 18 | 🌐 Python | 📅 2023-09-02 - An open source differentiable dense SLAM library for PyTorch.
* [rovio](https://github.com/ethz-asl/rovio) ⭐ 1,262 | 🐛 83 | 🌐 C++ | 📅 2026-01-19 - Robust Visual Inertial Odometry Framework.
* [xivo](https://github.com/ucla-vision/xivo) ⭐ 891 | 🐛 16 | 🌐 C++ | 📅 2023-02-24 - X Inertial-aided Visual Odometry.
* [CubeSLAM and ORB SLAM](https://github.com/shichaoy/cube_slam) ⭐ 885 | 🐛 35 | 🌐 C++ | 📅 2020-11-24 - Monocular 3D Object Detection and SLAM Package of CubeSLAM and ORB SLAM.
* [LARVIO](https://github.com/PetWorm/LARVIO) ⭐ 804 | 🐛 12 | 🌐 C++ | 📅 2024-04-10 - A lightweight, accurate and robust monocular visual inertial odometry based on Multi-State Constraint Kalman Filter.
* [ESVO](https://github.com/HKUST-Aerial-Robotics/ESVO) ⭐ 504 | 🐛 10 | 🌐 C++ | 📅 2025-03-20 - A novel pipeline for real-time visual odometry using a stereo event-based camera.
* [vilib](https://github.com/uzh-rpg/vilib) ⭐ 458 | 🐛 4 | 🌐 C++ | 📅 2021-06-25 - This library focuses on the front-end of VIO pipelines with CUDA.
* [tagslam](https://github.com/berndpfrommer/tagslam) ⭐ 369 | 🐛 0 | 🌐 C++ | 📅 2026-01-08 - A ROS-based package for Simultaneous Localization and Mapping using AprilTag fiducial markers.
* [fiducials](https://github.com/UbiquityRobotics/fiducials) ⭐ 284 | 🐛 38 | 🌐 C | 📅 2025-11-27 - Simultaneous localization and mapping using fiducial markers.
* [viso2](https://github.com/srv/viso2) ⭐ 253 | 🐛 17 | 🌐 C++ | 📅 2026-02-03 - A ROS wrapper for libviso2, a library for visual odometry.
* [orbslam-map-saving-extension](https://github.com/TUMFTM/orbslam-map-saving-extension) ⭐ 251 | 🐛 7 | 🌐 C++ | 📅 2020-07-17 - In this extensions the map of ORB-features be saved to the disk as a reference for future runs along the same track.
* [orb\_slam\_2\_ros](https://github.com/appliedAI-Initiative/orb_slam_2_ros) - A ROS implementation of ORB\_SLAM2.
* [basalt](https://gitlab.com/VladyslavUsenko/basalt) - Visual-Inertial Mapping with Non-Linear Factor Recovery.

### Vector Map

* [Mapbox](https://github.com/mapbox/mapbox-gl-js) ⭐ 12,384 | 🐛 1,456 | 🌐 TypeScript | 📅 2026-08-19 - A JavaScript library for interactive, customizable vector maps on the web.
* [osrm-backend](https://github.com/Project-OSRM/osrm-backend) ⭐ 7,989 | 🐛 357 | 🌐 C++ | 📅 2026-08-17 - Open Source Routing Machine - C++ backend.
* [gdal](https://github.com/OSGeo/gdal) ⭐ 6,022 | 🐛 565 | 🌐 C++ | 📅 2026-08-19 - GDAL is an open source X/MIT licensed translator library for raster and vector geospatial data formats.
* [osmnx](https://github.com/gboeing/osmnx) ⭐ 5,816 | 🐛 1 | 🌐 Python | 📅 2026-07-31 - Python for street networks. Retrieve, model, analyze, and visualize street networks and other spatial data from OpenStreetMap.
* [geopandas](https://github.com/geopandas/geopandas) ⭐ 5,227 | 🐛 431 | 🌐 Python | 📅 2026-08-12 - A project to add support for geographic data to pandas objects.
* [mapnik](https://github.com/mapnik/mapnik) ⭐ 3,955 | 🐛 729 | 🌐 C++ | 📅 2026-08-07 - Combines pixel-perfect image output with lightning-fast cartographic algorithms, and exposes interfaces in C++, Python, and Node.
* [iD](https://github.com/openstreetmap/iD) ⭐ 3,858 | 🐛 982 | 🌐 JavaScript | 📅 2026-08-19 - The easy-to-use OpenStreetMap editor in JavaScript.
* [MapsModelsImporter](https://github.com/eliemichel/MapsModelsImporter) ⭐ 2,803 | 🐛 132 | 🌐 Python | 📅 2024-04-21 - A Blender add-on to import models from google maps.
* [3d-tiles](https://github.com/CesiumGS/3d-tiles) ⭐ 2,589 | 🐛 97 | 🌐 Batchfile | 📅 2026-08-17 - Specification for streaming massive heterogeneous 3D geospatial datasets.
* [grass](https://github.com/OSGeo/grass) ⭐ 1,153 | 🐛 705 | 🌐 C | 📅 2026-08-19 - GRASS GIS - free and open source Geographic Information System (GIS).
* [segmap](https://github.com/ethz-asl/segmap) ⭐ 1,096 | 🐛 66 | 🌐 C++ | 📅 2021-03-17 - A map representation based on 3D segments.
* [Lanelet2](https://github.com/fzi-forschungszentrum-informatik/Lanelet2) ⭐ 957 | 🐛 19 | 🌐 C++ | 📅 2026-06-18 - Map handling framework for automated driving.
* [barefoot](https://github.com/bmwcarit/barefoot) ⭐ 692 | 🐛 58 | 🌐 Java | 📅 2023-04-14 -  Online and Offline map matching that can be used stand-alone and in the cloud.
* [RapiD](https://github.com/facebookincubator/RapiD) ⭐ 634 | 🐛 335 | 🌐 JavaScript | 📅 2026-05-28 - An enhanced version of iD for mapping with AI created by Facebook.
* [mapillary\_tools](https://github.com/mapillary/mapillary_tools) ⭐ 314 | 🐛 30 | 🌐 Python | 📅 2026-08-04 - A library for processing and uploading images to Mapillary.
* [MapToolbox](https://github.com/autocore-ai/MapToolbox) ⭐ 291 | 🐛 34 | 🌐 C# | 📅 2026-07-15 - Plugins to make Autoware vector maps in Unity.
* [assuremapingtools](https://github.com/hatem-darweesh/assuremapingtools) ⭐ 234 | 🐛 17 | 🌐 Dockerfile | 📅 2024-08-29 -  Desktop based tool for viewing, editing and saving road network maps for autonomous vehicle platforms such as Autoware.
* [imagery-index](https://github.com/ideditor/imagery-index) ⭐ 29 | 🐛 9 | 🌐 JavaScript | 📅 2025-11-04 - An index of aerial and satellite imagery useful for mapping.
* [OpenDRIVE](http://www.opendrive.org/index.html) - An open file format for the logical description of road networks.

## Prediction

* [Awesome-Interaction-aware-Trajectory-Prediction](https://github.com/jiachenli94/Awesome-Interaction-aware-Trajectory-Prediction) ⭐ 1,690 | 🐛 1 | 🌐 TeX | 📅 2024-09-28 - A selection of state-of-the-art research materials on trajectory prediction.
* [sgan](https://github.com/agrimgupta92/sgan) ⭐ 915 | 🐛 70 | 🌐 Python | 📅 2023-11-24 -  Socially Acceptable Trajectories with Generative Adversarial Networks.

## Behavior and Decision

* [BehaviorTree.CPP](https://github.com/BehaviorTree/BehaviorTree.CPP) ⭐ 4,163 | 🐛 56 | 🌐 C++ | 📅 2026-08-14 - Behavior Trees Library in C++.
* [Groot](https://github.com/BehaviorTree/Groot) ⭐ 886 | 🐛 66 | 🌐 C++ | 📅 2025-02-28 - Graphical Editor to create BehaviorTrees. Compliant with BehaviorTree.CPP.
* [ROSPlan](https://github.com/KCL-Planning/ROSPlan) ⭐ 394 | 🐛 62 | 🌐 C++ | 📅 2024-02-07 - Generic framework for task planning in a ROS system.
* [ad-rss-lib](https://github.com/intel/ad-rss-lib) ⚠️ Archived - Library implementing the Responsibility Sensitive Safety model (RSS) for Autonomous Vehicles.
* [SMACC](https://github.com/reelrbtx/SMACC) ⭐ 327 | 🐛 9 | 🌐 C++ | 📅 2023-04-24 - An Event-Driven, Asynchronous, Behavioral State Machine Library for real-time ROS (Robotic Operating System) applications written in C++ .
* [py\_trees\_ros](https://github.com/splintered-reality/py_trees_ros) ⭐ 228 | 🐛 20 | 🌐 Python | 📅 2026-07-16 - Behaviours, trees and utilities that extend py\_trees for use with ROS.
* [RAFCON](https://github.com/DLR-RM/RAFCON) ⭐ 211 | 🐛 9 | 🌐 Python | 📅 2026-08-11 - Uses hierarchical state machines, featuring concurrent state execution, to represent robot programs.
* [sts\_bt\_library](https://github.com/Autonomous-Logistics/sts_bt_library) ⭐ 21 | 🐛 1 | 🌐 C++ | 📅 2020-04-08 - This library provides the functionality to set up your own behavior tree logic by using the defined tree structures like Fallback, Sequence or Parallel Nodes.
* [FlexBE](https://flexbe.github.io/) - Graphical editor for hierarchical state machines, based on ROS's smach.

## Planning and Control

* [pinocchio](https://github.com/stack-of-tasks/pinocchio) ⭐ 3,662 | 🐛 107 | 🌐 C++ | 📅 2026-08-11 - A fast and flexible implementation of Rigid Body Dynamics algorithms and their analytical derivatives.
* [EGO-Planner](https://github.com/ZJU-FAST-Lab/ego-planner) ⭐ 2,607 | 🐛 40 | 🌐 C++ | 📅 2025-03-08 - A lightweight gradient-based local planner without ESDF construction, which significantly reduces computation time compared to some state-of-the-art methods.
* [casADi](https://github.com/casadi/casadi) ⭐ 2,273 | 🐛 739 | 🌐 C++ | 📅 2026-08-17 - A symbolic framework for numeric optimization implementing automatic differentiation in forward and reverse modes on sparse matrix-valued computational graphs.
* [ompl](https://github.com/ompl/ompl) ⭐ 2,126 | 🐛 99 | 🌐 C++ | 📅 2026-08-14 - Consists of many state-of-the-art sampling-based motion planning algorithms.
* [path\_planner](https://github.com/karlkurzer/path_planner) ⭐ 1,908 | 🐛 18 | 🌐 C++ | 📅 2026-03-30 - Hybrid A\* Path Planner for the KTH Research Concept Vehicle.
* [mpcc](https://github.com/alexliniger/MPCC) ⭐ 1,857 | 🐛 9 | 🌐 C++ | 📅 2026-04-25 - Model Predictive Contouring Controller for Autonomous Racing.
* [flexible-collision-library](https://github.com/flexible-collision-library/fcl) ⭐ 1,749 | 🐛 244 | 🌐 C++ | 📅 2026-06-03 - A library for performing three types of proximity queries on a pair of geometric models composed of triangles.
* [control-toolbox](https://github.com/ethz-adrl/control-toolbox) ⭐ 1,704 | 🐛 64 | 🌐 C++ | 📅 2022-11-09 - An efficient C++ library for control, estimation, optimization and motion planning in robotics.
* [tinyspline](https://github.com/msteinbeck/tinyspline) ⭐ 1,349 | 🐛 26 | 🌐 C | 📅 2024-09-03 - TinySpline is a small, yet powerful library for interpolating, transforming, and querying arbitrary NURBS, B-Splines, and Bézier curves.
* [teb\_local\_planner](https://github.com/rst-tu-dortmund/teb_local_planner) ⭐ 1,339 | 🐛 152 | 🌐 C++ | 📅 2026-01-09 - An optimal trajectory planner considering distinctive topologies for mobile robots based on Timed-Elastic-Bands.
* [Open Source Car Control](https://github.com/PolySync/oscc) ⭐ 1,037 | 🐛 15 | 🌐 C++ | 📅 2019-12-10 -  An assemblage of software and hardware designs that enable computer control of modern cars in order to facilitate the development of autonomous vehicle technology.
* [toppra](https://github.com/hungpham2511/toppra) ⭐ 922 | 🐛 41 | 🌐 Python | 📅 2026-07-28 - A library for computing the time-optimal path parametrization for robots subject to kinematic and dynamic constraints.
* [openrave](https://github.com/rdiankov/openrave) ⭐ 815 | 🐛 349 | 🌐 C++ | 📅 2026-08-12 - Open Robotics Automation Virtual Environment: An environment for testing, developing, and deploying robotics motion planning algorithms.
* [CrowdNav](https://github.com/vita-epfl/CrowdNav) ⭐ 729 | 🐛 30 | 🌐 Python | 📅 2022-08-26 - Crowd-aware Robot Navigation with Attention-based Deep Reinforcement Learning.
* [OpEn](https://github.com/alphaville/optimization-engine) ⭐ 643 | 🐛 12 | 🌐 Rust | 📅 2026-03-31 - A solver for Fast & Accurate Embedded Optimization for next-generation Robotics and Autonomous Systems.
* [global\_racetrajectory\_optimization](https://github.com/TUMFTM/global_racetrajectory_optimization) ⭐ 602 | 🐛 9 | 🌐 Python | 📅 2023-07-06 - This repository contains multiple approaches for generating global racetrajectories.
* [se2\_navigation](https://github.com/leggedrobotics/se2_navigation) ⭐ 602 | 🐛 7 | 🌐 C++ | 📅 2023-03-07 - Pure pursuit controller and Reeds-Shepp sampling based planner for navigation in SE(2) space.
* [ACADO Toolkit](https://github.com/acado/acado) ⭐ 584 | 🐛 150 | 🌐 C++ | 📅 2024-08-14 - A software environment and algorithm collection for automatic control and dynamic optimization.
* [ilqr](https://github.com/anassinator/ilqr) ⭐ 424 | 🐛 7 | 🌐 Python | 📅 2022-06-21 - Iterative Linear Quadratic Regulator with auto-differentiatiable dynamics models.
* [pykep](https://github.com/esa/pykep) ⭐ 421 | 🐛 4 | 🌐 C++ | 📅 2026-07-07 - A scientific library providing basic tools for research in interplanetary trajectory design.
* [mb planner](https://github.com/unr-arl/mbplanner_ros) ⭐ 360 | 🐛 5 | 🌐 C++ | 📅 2023-04-19 - Aerial vehicle planner for tight spaces. Used in DARPA SubT Challenge.
* [GraphBasedLocalTrajectoryPlanner](https://github.com/TUMFTM/GraphBasedLocalTrajectoryPlanner) ⭐ 267 | 🐛 3 | 🌐 Python | 📅 2023-07-06 - Was used on a real race vehicle during the Roborace Season Alpha and achieved speeds above 200km/h.
* [rrt](https://github.com/RoboJackets/rrt) ⚠️ Archived - C++ RRT (Rapidly-exploring Random Tree) implementation.
* [steering\_functions](https://github.com/hbanzhaf/steering_functions) ⭐ 256 | 🐛 2 | 🌐 C++ | 📅 2024-06-29 - Contains a C++ library that implements steering functions for car-like robots with limited turning radius.
* [aikido](https://github.com/personalrobotics/aikido) ⭐ 233 | 🐛 100 | 🌐 C++ | 📅 2023-03-10 - Artificial Intelligence for Kinematics, Dynamics, and Optimization.
* [am\_traj](https://github.com/ZJU-FAST-Lab/am_traj) ⭐ 194 | 🐛 0 | 🌐 C++ | 📅 2021-06-10 - Alternating Minimization Based Trajectory Generation for Quadrotor Aggressive Flight.
* [autogenu-jupyter](https://github.com/mayataka/autogenu-jupyter) ⭐ 179 | 🐛 1 | 🌐 C++ | 📅 2026-07-14 - This project provides the continuation/GMRES method (C/GMRES method) based solvers for nonlinear model predictive control (NMPC) and an automatic code generator for NMPC.
* [traffic-editor](https://github.com/osrf/traffic-editor) ⭐ 165 | 🐛 43 | 🌐 C++ | 📅 2026-06-22 - A graphical editor for robot traffic flows.
* [rmf\_core](https://github.com/osrf/rmf_core) ⚠️ Archived - The rmf\_core packages provide the centralized functions of the Robotics Middleware Framework (RMF).
* [open\_street\_map](https://github.com/ros-geographic-info/open_street_map) ⭐ 91 | 🐛 10 | 🌐 Python | 📅 2023-01-18 - ROS packages for working with Open Street Map geographic information.
* [fastrack](https://github.com/HJReachability/fastrack) ⭐ 80 | 🐛 2 | 🌐 C++ | 📅 2020-08-03 - A ROS implementation of Fast and Safe Tracking (FaSTrack).
* [pacmod](https://github.com/astuff/pacmod) ⭐ 30 | 🐛 1 | 🌐 C++ | 📅 2023-04-28 -  Designed to allow the user to control a vehicle with the PACMod drive-by-wire system.
* [dual quaternions ros](https://github.com/Achllle/dual_quaternions_ros) ⭐ 30 | 🐛 9 | 🌐 Python | 📅 2020-08-14 - ROS python package for dual quaternion SLERP.
* [HypridAStarTrailer](https://github.com/AtsushiSakai/HybridAStarTrailer) - A path planning algorithm based on Hybrid A\* for trailer truck.
* [commonroad](https://commonroad.in.tum.de/) - Composable benchmarks for motion planning on roads.
* [moveit](https://moveit.ros.org/) - Easy-to-use robotics manipulation platform for developing applications, evaluating designs, and building integrated products.
* [Ruckig](https://ruckig.com) - Instantaneous Motion Generation. Real-time. Jerk-constrained. Time-optimal.

## User Interaction

### Graphical User Interface

* [imgui](https://github.com/ocornut/imgui) ⭐ 75,728 | 🐛 1,234 | 🌐 C++ | 📅 2026-08-19 - Designed to enable fast iterations and to empower programmers to create content creation tools and visualization / debug tools.
* [pencil](https://github.com/evolus/pencil) ⭐ 9,855 | 🐛 534 | 🌐 JavaScript | 📅 2026-06-02 - A tool for making diagrams and GUI prototyping that everyone can use.
* [NanoGUI](https://github.com/wjakob/nanogui) ⭐ 4,871 | 🐛 115 | 🌐 C++ | 📅 2023-04-28 - A minimalistic cross-platform widget library for OpenGL 3.x or higher.
* [elements](https://github.com/cycfi/elements) ⭐ 3,719 | 🐛 41 | 🌐 C++ | 📅 2026-06-13 - A lightweight, fine-grained, resolution independent, modular GUI library.
* [cage](https://github.com/Hjdskes/cage) ⭐ 2,013 | 🐛 123 | 🌐 C | 📅 2026-08-18 - This is Cage, a Wayland kiosk. A kiosk runs a single, maximized application.
* [chilipie](https://github.com/futurice/chilipie-kiosk) ⭐ 1,399 | 🐛 69 | 🌐 HTML | 📅 2022-04-04 - Easy-to-use Raspberry Pi image for booting directly into full-screen Chrome.
* [qtpy](https://github.com/spyder-ide/qtpy) ⭐ 1,101 | 🐛 38 | 🌐 Python | 📅 2026-04-12 - Provides an uniform layer to support PyQt5, PySide2, PyQt4 and PySide with a single codebase.
* [mir](https://github.com/MirServer/mir) ⭐ 778 | 🐛 413 | 🌐 C++ | 📅 2026-08-19 - Mir is set of libraries for building Wayland based shells.
* [ddynamic\_reconfigure](https://github.com/pal-robotics/ddynamic_reconfigure) ⭐ 102 | 🐛 7 | 🌐 C++ | 📅 2025-04-22 - Allows modifying parameters of a ROS node using the dynamic\_reconfigure framework without having to write cfg files.
* [rqt](https://wiki.ros.org/rqt) - A Qt-based framework for GUI development for ROS. It consists of three parts/metapackages.
* [dynamic\_reconfigure](https://wiki.ros.org/dynamic_reconfigure) - The focus of dynamic\_reconfigure is on providing a standard way to expose a subset of a node's parameters to external reconfiguration.

### Acoustic User Interface

* [TTS](https://github.com/coqui-ai/TTS) ⭐ 45,916 | 🐛 2 | 🌐 Python | 📅 2024-08-16 - A deep learning toolkit for Text-to-Speech, battle-tested in research and production.
* [DeepSpeech](https://github.com/mozilla/DeepSpeech) ⚠️ Archived - An open source Speech-To-Text engine, using a model trained by machine learning techniques based on Baidu's Deep Speech research paper.
* [mycroft-core](https://github.com/MycroftAI/mycroft-core) ⚠️ Archived - Mycroft is a hackable open source voice assistant.
* [DDSP](https://github.com/magenta/ddsp) ⭐ 3,340 | 🐛 54 | 🌐 Python | 📅 2026-07-09 - A library of differentiable versions of common DSP functions (such as synthesizers, waveshapers, and filters).
* [waveglow](https://github.com/NVIDIA/waveglow) ⭐ 2,339 | 🐛 79 | 🌐 Python | 📅 2023-10-19 - A Flow-based Generative Network for Speech Synthesis.
* [pyo](https://github.com/belangeo/pyo) ⭐ 1,447 | 🐛 32 | 🌐 Python | 📅 2026-07-20 - A Python module written in C containing classes for a wide variety of audio signal processing types.
* [rhasspy](https://github.com/synesthesiam/rhasspy) ⚠️ Archived - Rhasspy (pronounced RAH-SPEE) is an offline, multilingual voice assistant toolkit inspired by Jasper that works well with Home Assistant, Hass.io, and Node-RED.
* [NoiseTorch](https://github.com/lawl/NoiseTorch) ⚠️ Archived - Creates a virtual microphone that suppresses noise, in any application.

### Command Line Interface

* [the-art-of-command-line](https://github.com/jlevy/the-art-of-command-line) ⭐ 162,124 | 🐛 256 | 📅 2024-06-25 - Master the command line, in one page.
* [fzf](https://github.com/junegunn/fzf) ⭐ 82,578 | 🐛 327 | 🌐 Go | 📅 2026-08-17 - A command-line fuzzy finder.
* [bat](https://github.com/sharkdp/bat) ⭐ 60,215 | 🐛 422 | 🌐 Rust | 📅 2026-08-11 - A cat(1) clone with wings.
* [ag](https://github.com/ggreer/the_silver_searcher) ⭐ 27,103 | 🐛 564 | 🌐 C | 📅 2024-06-16 - A code-searching tool similar to ack, but faster.
* [fx](https://github.com/antonmedv/fx) ⭐ 20,584 | 🐛 25 | 🌐 Go | 📅 2026-07-28 - Command-line tool and terminal JSON viewer.
* [gocui](https://github.com/jroimartin/gocui) ⭐ 10,593 | 🐛 60 | 🌐 Go | 📅 2025-05-01 - Minimalist Go package aimed at creating Console User Interfaces.
* [python-prompt-toolkit](https://github.com/prompt-toolkit/python-prompt-toolkit) ⭐ 10,556 | 🐛 705 | 🌐 Python | 📅 2026-07-26 - Library for building powerful interactive command line applications in Python.
* [mapscii](https://github.com/rastapasta/mapscii) ⭐ 9,222 | 🐛 52 | 🌐 JavaScript | 📅 2024-11-03 - World map renderer for your console.
* [dotbot](https://github.com/anishathalye/dotbot) ⭐ 7,991 | 🐛 17 | 🌐 Python | 📅 2026-07-12 - A tool that bootstraps your dotfiles.
* [tmate](https://github.com/tmate-io/tmate) ⭐ 6,110 | 🐛 129 | 🌐 C | 📅 2026-07-29 - Instant terminal sharing.
* [guake](https://github.com/Guake/guake) ⭐ 4,667 | 🐛 453 | 🌐 Python | 📅 2026-08-19 - Drop-down terminal for GNOME.
* [tmuxp](https://github.com/tmux-python/tmuxp) ⭐ 4,560 | 🐛 138 | 🌐 Python | 📅 2026-08-16 -  A session manager built on libtmux.
* [asciimatics](https://github.com/peterbrittain/asciimatics) ⭐ 4,301 | 🐛 17 | 🌐 Python | 📅 2026-07-04 - A cross platform package to do curses-like operations, plus higher level APIs and widgets to create text UIs and ASCII art animations.
* [wemux](https://github.com/zolrath/wemux) ⭐ 3,673 | 🐛 37 | 🌐 Shell | 📅 2022-10-03 - Multi-User Tmux Made Easy.
* [TerminalImageViewer](https://github.com/stefanhaustein/TerminalImageViewer) ⭐ 1,683 | 🐛 17 | 🌐 C++ | 📅 2026-08-03 - Small C++ program to display images in a (modern) terminal using RGB ANSI codes and unicode block graphics characters.
* [rosshow](https://github.com/dheera/rosshow) ⭐ 1,146 | 🐛 6 | 🌐 Python | 📅 2025-12-29 - Visualize ROS topics inside a terminal with Unicode/ASCII art.
* [pkgtop](https://github.com/orhun/pkgtop) ⭐ 346 | 🐛 0 | 🌐 Go | 📅 2025-04-20 - Interactive package manager and resource monitor designed for the GNU/Linux.
* [dotfiles of cornerman](https://github.com/cornerman/dotfiles) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2023-09-02 - Powerful zsh and vim dotfiles.
* [prompt-hjem](https://github.com/cornerman/prompt-hjem) ⭐ 7 | 🐛 2 | 🌐 Makefile | 📅 2019-04-03 - A beautiful zsh prompt.
* [terminator](https://launchpad.net/terminator) - The goal of this project is to produce a useful tool for arranging terminals.

## Data Visualization and Mission Control

* [obs-studio](https://github.com/obsproject/obs-studio) ⭐ 75,195 | 🐛 1,179 | 🌐 C | 📅 2026-08-15 - Free and open source software for live streaming and screen recording.
* [bokeh](https://github.com/bokeh/bokeh) ⭐ 20,432 | 🐛 852 | 🌐 Python | 📅 2026-08-18 - Interactive Data Visualization in the browser, from Python.
* [plotly.py](https://github.com/plotly/plotly.py) ⭐ 18,748 | 🐛 779 | 🌐 Python | 📅 2026-08-07 - An open-source, interactive graphing library for Python.
* [openmct](https://github.com/nasa/openmct) ⭐ 13,085 | 🐛 1,068 | 🌐 JavaScript | 📅 2026-08-18 - A web based mission control framework.
* [kepler.gl](https://github.com/keplergl/kepler.gl) ⭐ 11,976 | 🐛 461 | 🌐 TypeScript | 📅 2026-08-19 - Kepler.gl is a powerful open source geospatial analysis tool for large-scale data sets.
* [PlotJuggler](https://github.com/facontidavide/PlotJuggler) ⭐ 6,120 | 🐛 157 | 🌐 C++ | 📅 2026-08-10 - The timeseries visualization tool that you deserve.
* [voila](https://github.com/voila-dashboards/voila) ⭐ 5,940 | 🐛 328 | 🌐 Python | 📅 2026-08-03 - From Jupyter notebooks to standalone web applications and dashboards.
* [PyQtGraph](https://github.com/pyqtgraph/pyqtgraph) ⭐ 4,403 | 🐛 517 | 🌐 Python | 📅 2026-08-17 - Fast data visualization and GUI tools for scientific / engineering applications.
* [Pangolin](https://github.com/stevenlovegrove/Pangolin) ⭐ 2,736 | 🐛 48 | 🌐 C++ | 📅 2026-08-19 - Pangolin is a lightweight portable rapid development library for managing OpenGL display / interaction and abstracting video input.
* [webviz](https://github.com/cruise-automation/webviz) ⭐ 2,326 | 🐛 134 | 🌐 JavaScript | 📅 2022-12-17 - Web-based visualization libraries like rviz.
* [marvros](https://github.com/mavlink/mavros) ⭐ 1,211 | 🐛 410 | 🌐 C++ | 📅 2026-08-14 - MAVLink to ROS gateway with proxy for Ground Control Station.
* [streetscape.gl](https://github.com/uber/streetscape.gl) ⭐ 995 | 🐛 114 | 🌐 JavaScript | 📅 2024-07-04 - Streetscape.gl is a toolkit for visualizing autonomous and robotics data in the XVIZ protocol.
* [xdot](https://github.com/jrfonseca/xdot.py) ⭐ 940 | 🐛 15 | 🌐 Python | 📅 2026-03-19 - Interactive viewer for graphs written in Graphviz's dot language.
* [urdf-loaders](https://github.com/gkjohnson/urdf-loaders) ⭐ 811 | 🐛 31 | 🌐 JavaScript | 📅 2026-08-10 - URDF Loaders for Unity and THREE.js with example ATHLETE URDF File.
* [ROS-Mobile](https://github.com/ROS-Mobile/ROS-Mobile-Android) ⭐ 540 | 🐛 35 | 🌐 Java | 📅 2023-12-02 - Visualization and controlling application for Android.
* [ipygany](https://github.com/QuantStack/ipygany) ⭐ 494 | 🐛 43 | 🌐 Python | 📅 2023-07-20 - 3-D Scientific Visualization in the Jupyter Notebook.
* [ros3djs](https://github.com/RobotWebTools/ros3djs) ⭐ 443 | 🐛 81 | 🌐 JavaScript | 📅 2026-02-20 - 3D Visualization Library for use with the ROS JavaScript Libraries.
* [web\_video\_server](https://github.com/RobotWebTools/web_video_server) ⭐ 388 | 🐛 24 | 🌐 C++ | 📅 2026-07-02 - HTTP Streaming of ROS Image Topics in Multiple Formats.
* [RVizWeb](https://github.com/osrf/rvizweb) ⭐ 321 | 🐛 24 | 🌐 HTML | 📅 2022-11-15 - Provides a convenient way of building and launching a web application with features similar to RViz.
* [Foxglove Studio](https://github.com/foxglove/studio) ⚠️ Archived - Web and desktop app for robotics visualization and debugging; actively maintained fork of webviz.
* [qgis\_ros](https://github.com/locusrobotics/qgis_ros) ⭐ 47 | 🐛 7 | 🌐 Python | 📅 2023-11-09 - Access bagged and live topic data in a highly featured GIS environment.
* [guacamole](https://guacamole.apache.org/) - Clientless remote desktop gateway. It supports standard protocols like VNC, RDP, and SSH.
* [rqt\_bag](http://wiki.ros.org/rqt_bag) - Provides a GUI plugin for displaying and replaying ROS bag files.
* [octave](https://www.gnu.org/software/octave/) - Provides a convenient command line interface for solving linear and nonlinear problems numerically, and for performing other numerical experiments using a language that is mostly compatible with Matlab.
* [K3D-tools](https://github.com/K3D-tools) - Jupyter notebook extension for 3D visualization.

### Annotation

* [label-studio](https://github.com/heartexlabs/label-studio) ⭐ 28,085 | 🐛 925 | 🌐 TypeScript | 📅 2026-08-19 - Label Studio is a multi-type data labeling and annotation tool with standardized output format.
* [LabelImg](https://github.com/tzutalin/labelImg) ⚠️ Archived - A graphical image annotation tool and label object bounding boxes in images.
* [cvat](https://github.com/opencv/cvat) ⭐ 16,547 | 🐛 586 | 🌐 Python | 📅 2026-08-19 - Powerful and efficient Computer Vision Annotation Tool (CVAT).
* [labelme](https://github.com/wkentaro/labelme) ⭐ 16,110 | 🐛 184 | 🌐 Python | 📅 2026-08-19 - Image Polygonal Annotation with Python (polygon, rectangle, circle, line, point and image-level flag annotation).
* [napari](https://github.com/napari/napari) ⭐ 2,735 | 🐛 1,233 | 🌐 Python | 📅 2026-08-19 -  A fast, interactive, multi-dimensional image viewer for python.
* [universal-data-tool](https://github.com/UniversalDataTool/universal-data-tool) ⭐ 2,071 | 🐛 168 | 🌐 JavaScript | 📅 2025-03-15 - Collaborate & label any type of data, images, text, or documents, in an easy web interface or desktop app.
* [semantic-segmentation-editor](https://github.com/Hitachi-Automotive-And-Industry-Lab/semantic-segmentation-editor) ⭐ 1,970 | 🐛 62 | 🌐 JavaScript | 📅 2024-09-18 - A web based labeling tool for creating AI training data sets (2D and 3D).
* [PixelAnnotationTool](https://github.com/abreheret/PixelAnnotationTool) ⭐ 1,455 | 🐛 23 | 🌐 C++ | 📅 2022-11-21 - Annotate quickly images.
* [3d-bat](https://github.com/walzimmer/3d-bat) ⭐ 818 | 🐛 47 | 🌐 TypeScript | 📅 2024-03-07 - 3D Bounding Box Annotation Tool for Point cloud and Image Labeling.
* [point\_labeler](https://github.com/jbehley/point_labeler) ⭐ 751 | 🐛 10 | 🌐 C++ | 📅 2025-03-19 - Tool for labeling of a single point clouds or a stream of point clouds.
* [BMW-Labeltool-Lite](https://github.com/BMW-InnovationLab/BMW-Labeltool-Lite) ⭐ 323 | 🐛 11 | 🌐 C# | 📅 2024-07-26 - Provides you with a easy to use labeling tool for State-of-the-art Deep Learning training purposes.
* [3d-annotation-tool](https://github.com/StrayRobots/3d-annotation-tool) ⭐ 90 | 🐛 6 | 🌐 C++ | 📅 2022-06-27 - Lightweight tool to annotate point clouds with bounding boxes, rectangles, keypoints and more.
* [labelbox](https://github.com/Labelbox/labelbox) - The fastest way to annotate data to build and ship artificial intelligence applications.

### Point Cloud

* [Potree](https://github.com/potree/potree) ⭐ 5,577 | 🐛 822 | 🌐 JavaScript | 📅 2026-01-08 - WebGL point cloud viewer for large datasets.
* [CloudCompare](https://github.com/CloudCompare/CloudCompare) ⭐ 4,677 | 🐛 291 | 🌐 C++ | 📅 2026-08-18 - CloudCompare is a 3D point cloud (and triangular mesh) processing software.
* [polyscope](https://github.com/nmwsharp/polyscope) ⭐ 2,196 | 🐛 127 | 🌐 C++ | 📅 2026-05-20 - A C++ & Python viewer for 3D data like meshes and point clouds.
* [Pcx](https://github.com/keijiro/Pcx) ⭐ 1,513 | 🐛 25 | 🌐 C# | 📅 2022-08-23 - Point cloud importer & renderer for Unity.
* [entwine](https://github.com/connormanning/entwine/) ⭐ 526 | 🐛 3 | 🌐 C++ | 📅 2026-06-02 - A data organization library for massive point clouds, designed to conquer datasets of trillions of points as well as desktop-scale point clouds.
* [point\_cloud\_viewer](https://github.com/googlecartographer/point_cloud_viewer) ⭐ 359 | 🐛 30 | 🌐 Rust | 📅 2022-06-17 - Makes viewing massive point clouds easy and convenient.
* [VeloView](https://github.com/Kitware/VeloView) ⭐ 330 | 🐛 61 | 🌐 C++ | 📅 2021-09-29 - Performs real-time visualization of live captured 3D LiDAR data from Velodyne's HDL sensors.
* [LidarView](https://github.com/Kitware/LidarView) ⭐ 302 | 🐛 6 | 🌐 C++ | 📅 2026-06-16 - Performs real-time visualization and easy processing of live captured 3D LiDAR data from Lidar sensors.
* [ImmersivePoints](https://github.com/rmeertens/ImmersivePoints) ⭐ 15 | 🐛 0 | 🌐 HTML | 📅 2026-01-27 - A web-application for virtual reality devices to explore 3D data in the most natural way possible.

### RViz

* [rviz\_visual\_tools](https://github.com/PickNikRobotics/rviz_visual_tools) ⭐ 819 | 🐛 34 | 🌐 C++ | 📅 2026-08-03 - C++ API wrapper for displaying shapes and meshes in Rviz.
* [rviz\_satellite](https://github.com/gareth-cross/rviz_satellite) ⭐ 667 | 🐛 14 | 🌐 C++ | 📅 2026-05-15 - Display internet satellite imagery in RViz.
* [mapviz](https://github.com/swri-robotics/mapviz) ⭐ 484 | 🐛 9 | 🌐 C++ | 📅 2026-08-19 - Modular ROS visualization tool for 2D data.
* [rviz\_cinematographer](https://github.com/AIS-Bonn/rviz_cinematographer) ⭐ 291 | 🐛 2 | 🌐 C++ | 📅 2021-08-19 - Easy to use tools to create and edit trajectories for the rviz camera.

<!--lint ignore double-link-->

* [jsk\_visualization](https://github.com/jsk-ros-pkg/jsk_visualization) ⭐ 357 | 🐛 29 | 🌐 C++ | 📅 2026-07-29 - Jsk visualization ros packages for rviz and rqt.
* [xpp](https://github.com/leggedrobotics/xpp) ⭐ 338 | 🐛 8 | 🌐 C++ | 📅 2021-12-09 - Visualization of motion-plans for legged robots.
* [moveit\_visual\_tools](https://github.com/ros-planning/moveit_visual_tools) ⭐ 172 | 🐛 10 | 🌐 C++ | 📅 2026-08-03 - Helper functions for displaying and debugging MoveIt! data in Rviz via published markers.
* [rviz stereo](http://wiki.ros.org/rviz/Tutorials/Rviz%20in%20Stereo) - 3D stereo rendering displays a different view to each eye so that the scene appears to have depth.

## Operation System

### Monitoring

* [spdlog](https://github.com/gabime/spdlog) ⭐ 29,496 | 🐛 49 | 🌐 C++ | 📅 2026-08-08 - Very fast, header-only/compiled, C++ logging library.
* [ctop](https://github.com/bcicen/ctop) ⭐ 17,826 | 🐛 121 | 🌐 Go | 📅 2024-07-08 -  Top-like interface for container metrics.
* [psutil](https://github.com/giampaolo/psutil) ⭐ 11,265 | 🐛 255 | 🌐 Python | 📅 2026-08-17 - Cross-platform lib for process and system monitoring in Python.
* [nvtop](https://github.com/Syllo/nvtop) ⭐ 10,928 | 🐛 144 | 🌐 C | 📅 2026-05-06 - NVIDIA GPUs htop like monitoring tool.
* [ntop](https://github.com/ntop/ntopng) ⭐ 8,097 | 🐛 336 | 🌐 Lua | 📅 2026-08-19 - Web-based Traffic and Security Network Traffic Monitoring.
* [htop](https://github.com/hishamhm/htop) ⚠️ Archived - An interactive text-mode process viewer for Unix systems. It aims to be a better 'top'.
* [gpustat](https://github.com/wookayin/gpustat) ⭐ 4,392 | 🐛 30 | 🌐 Python | 📅 2026-05-30 -  A simple command-line utility for querying and monitoring GPU status.
* [collectd](https://github.com/collectd/collectd/) ⭐ 3,367 | 🐛 785 | 🌐 C | 📅 2026-05-29 - A small daemon which collects system information periodically and provides mechanisms to store and monitor the values in a variety of ways.
* [Sshwifty](https://github.com/nirui/sshwifty) ⭐ 3,118 | 🐛 40 | 🌐 JavaScript | 📅 2026-08-19 - Sshwifty is a SSH and Telnet connector made for the Web.
* [gputil](https://github.com/anderskm/gputil) ⭐ 1,214 | 🐛 31 | 🌐 Python | 📅 2026-07-18 - A Python module for getting the GPU status from NVIDA GPUs using nvidia-smi programmically in Python.
* [atop](https://github.com/Atoptool/atop) ⭐ 1,046 | 🐛 61 | 🌐 C | 📅 2026-08-15 - System and process monitor for Linux with logging and replay function.
* [jupyterlab-nvdashboard](https://github.com/rapidsai/jupyterlab-nvdashboard) ⭐ 680 | 🐛 33 | 🌐 TypeScript | 📅 2026-08-11 - A JupyterLab extension for displaying dashboards of GPU usage.
* [multimaster\_fkie](https://github.com/fkie/multimaster_fkie) ⭐ 289 | 🐛 12 | 🌐 Python | 📅 2025-03-11 - GUI-based management environment that is very useful to manage ROS-launch configurations and control running nodes.
* [rosmon](https://github.com/xqms/rosmon) ⭐ 201 | 🐛 18 | 🌐 C++ | 📅 2026-07-23 - ROS node launcher & monitoring daemon.
* [lnav](http://lnav.org/) - An enhanced log file viewer that takes advantage of any semantic information that can be gleaned from the files being viewed, such as timestamps and log levels.
* [ShellHub](https://www.shellhub.io) - ShellHub is a modern SSH server for remotely accessing linux devices via command line (using any SSH client) or web-based user interface, designed as an alternative to sshd. Think ShellHub as centralized SSH for the the edge and cloud computing.

### Database and Record

* [syncthing](https://github.com/syncthing/syncthing) ⭐ 87,781 | 🐛 376 | 🌐 Go | 📅 2026-08-19 - A continuous file synchronization program.
* [DuckDB](https://github.com/cwida/duckdb) ⭐ 40,430 | 🐛 806 | 🌐 C++ | 📅 2026-08-19 - An embeddable SQL OLAP Database Management System.
* [nextcloud](https://github.com/nextcloud/server) ⭐ 36,476 | 🐛 3,567 | 🌐 PHP | 📅 2026-08-19 - Nextcloud is a suite of client-server software for creating and using file hosting services.
* [borg](https://github.com/borgbackup/borg) ⭐ 13,626 | 🐛 262 | 🌐 Python | 📅 2026-08-19 - Deduplicating archiver with compression and authenticated encryption.
* [pykitti](https://github.com/utiasSTARS/pykitti) ⭐ 1,243 | 🐛 27 | 🌐 Python | 📅 2023-10-16 - Python tools for working with KITTI data.
* [xviz](https://github.com/uber/xviz) ⭐ 1,076 | 🐛 171 | 🌐 JavaScript | 📅 2024-07-05 - A protocol for real-time transfer and visualization of autonomy data.
* [kitti2bag](https://github.com/tomas789/kitti2bag) ⭐ 812 | 🐛 42 | 🌐 Python | 📅 2024-07-06 - Convert KITTI dataset to ROS bag file the easy way.
* [rosbag\_editor](https://github.com/facontidavide/rosbag_editor) ⭐ 447 | 🐛 12 | 🌐 C++ | 📅 2023-03-25 - Create a rosbag from a given one, using a simple GUI.
* [bag-database](https://github.com/swri-robotics/bag-database) ⚠️ Archived - A server that catalogs bag files and provides a web-based UI for accessing them.
* [ros\_numpy](https://github.com/eric-wieser/ros_numpy) ⭐ 320 | 🐛 21 | 🌐 Python | 📅 2023-11-22 - Tools for converting ROS messages to and from numpy arrays.
* [kitti\_to\_rosbag](https://github.com/ethz-asl/kitti_to_rosbag) ⭐ 258 | 🐛 7 | 🌐 C++ | 📅 2019-03-21 - A Dataset tools for working with the KITTI dataset raw data and converting it to a ROS bag. Also allows a library for direct access to poses, velodyne scans, and images.
* [ros\_type\_introspection](https://github.com/facontidavide/ros_type_introspection) ⚠️ Archived - Deserialize ROS messages that are unknown at compilation time.
* [kitti\_ros](https://github.com/LidarPerception/kitti_ros) ⭐ 34 | 🐛 10 | 🌐 Python | 📅 2021-02-14 - A ROS-based player to replay KiTTI dataset.
* [ncdu](https://dev.yorhel.nl/ncdu) - Ncdu is a disk usage analyzer with an ncurses interface.
* [marv-robotics](https://gitlab.com/ternaris/marv-robotics) - MARV Robotics is a powerful and extensible data management platform.
* [rqt\_bag\_exporter](https://gitlab.com/InstitutMaupertuis/rqt_bag_exporter) - Qt GUI to export ROS bag topics to files (CSV and/or video).

### Network Distributed File System

* [ceph](https://github.com/ceph/ceph) ⭐ 16,947 | 🐛 1,308 | 🌐 C++ | 📅 2026-08-19 - A distributed object, block, and file storage platform.
* [moosefs](https://github.com/moosefs/moosefs) ⭐ 1,996 | 🐛 190 | 🌐 C | 📅 2026-05-18 -  A scalable distributed storage system.
* [sshfs](https://github.com/osxfuse/sshfs) ⭐ 1,203 | 🐛 30 | 🌐 C | 📅 2022-09-06 - File system based on the SSH File Transfer Protocol.
* [nfs](https://github.com/sahlberg/libnfs) ⭐ 600 | 🐛 18 | 🌐 C | 📅 2026-08-08 - A distributed file system protocol originally developed by Sun Microsystems.
* [ansible-role-nfs](https://github.com/geerlingguy/ansible-role-nfs) ⭐ 280 | 🐛 3 | 🌐 Jinja | 📅 2025-11-28 - Installs NFS utilities on RedHat/CentOS or Debian/Ubuntu.

### Server Infrastructure and High Performance Computing

* [ansible](https://github.com/ansible/ansible) ⭐ 70,356 | 🐛 829 | 🌐 Python | 📅 2026-08-11 - Ansible is a radically simple IT automation platform that makes your applications and systems easier to deploy.
* [localstack](https://github.com/localstack/localstack) ⚠️ Archived - A fully functional local AWS cloud stack. Develop and test your cloud & Serverless apps offline.
* [traefik](https://github.com/containous/traefik) ⭐ 64,494 | 🐛 903 | 🌐 Go | 📅 2026-08-19 - The Cloud Native Edge Router.
* [Portainer](https://github.com/portainer/portainer) ⭐ 38,271 | 🐛 747 | 🌐 TypeScript | 📅 2026-08-18 - Making Docker management easy.
* [luigi](https://github.com/spotify/luigi) ⭐ 18,766 | 🐛 167 | 🌐 Python | 📅 2026-07-18 - A Python module that helps you build complex pipelines of batch jobs. It handles dependency resolution, workflow management, visualization etc. It also comes with Hadoop support built in.
* [nvidia-docker](https://github.com/NVIDIA/nvidia-docker) ⚠️ Archived - Build and run Docker containers leveraging NVIDIA GPUs.
* [kubeflow](https://github.com/kubeflow/kubeflow) ⭐ 15,822 | 🐛 0 | 📅 2026-07-10 - Machine Learning Toolkit for Kubernetes.
* [noVNC](https://github.com/novnc/noVNC) ⭐ 13,946 | 🐛 108 | 🌐 JavaScript | 📅 2026-06-06 - VNC client using HTML5.
* [triton-inference-server](https://github.com/NVIDIA/triton-inference-server) ⭐ 10,926 | 🐛 907 | 🌐 Python | 📅 2026-08-18 - NVIDIA Triton Inference Server provides a cloud inferencing solution optimized for NVIDIA GPUs.
* [cudf](https://github.com/rapidsai/cudf) ⭐ 9,730 | 🐛 1,316 | 🌐 C++ | 📅 2026-08-19 - Provides a pandas-like API that will be familiar to data engineers & data scientists, so they can use it to easily accelerate their workflows without going into the details of CUDA programming.
* [jupyterhub](https://github.com/jupyterhub/jupyterhub) ⭐ 8,327 | 🐛 196 | 🌐 Python | 📅 2026-08-14 - Multi-user server for Jupyter notebooks.
* [graylog2-server](https://github.com/Graylog2/graylog2-server) ⭐ 8,115 | 🐛 2,051 | 🌐 Java | 📅 2026-08-19 - Free and open source log management.
* [docker-py](https://github.com/docker/docker-py) ⭐ 7,209 | 🐛 565 | 🌐 Python | 📅 2026-08-13 - A Python library for the Docker Engine API.
* [pyinfra](https://github.com/Fizzadar/pyinfra) ⭐ 5,957 | 🐛 177 | 🌐 Python | 📅 2026-08-17 - It can be used for ad-hoc command execution, service deployment, configuration management and more.
* [Slurm](https://github.com/SchedMD/slurm) ⭐ 4,265 | 🐛 13 | 🌐 C | 📅 2026-08-19 - Slurm: A Highly Scalable Workload Manager.
* [polyaxon](https://github.com/polyaxon/polyaxon) ⭐ 3,719 | 🐛 126 | 🌐 MDX | 📅 2026-08-17 - A platform for reproducing and managing the whole life cycle of machine learning and deep learning applications.
* [docker-firefox](https://github.com/jlesage/docker-firefox) ⭐ 2,532 | 🐛 95 | 🌐 Shell | 📅 2026-08-17 - Run a Docker Container with Firefox and noVNC for remote access to headless servers.
* [log-pilot](https://github.com/AliyunContainerService/log-pilot) ⚠️ Archived - Collect logs for docker containers.
* [enroot](https://github.com/NVIDIA/enroot) ⭐ 1,090 | 🐛 99 | 🌐 Shell | 📅 2026-06-09 - A simple, yet powerful tool to turn traditional container/OS images into unprivileged sandboxes.
* [mass](https://github.com/maas/maas) ⭐ 493 | 🐛 18 | 🌐 Python | 📅 2026-08-19 - Self-service, remote installation of Windows, CentOS, ESXi and Ubuntu on real servers turns your data centre into a bare metal cloud.

### Embedded Operation System

* [jetson-containers](https://github.com/dusty-nv/jetson-containers) ⭐ 4,829 | 🐛 196 | 🌐 Jupyter Notebook | 📅 2026-08-10 - Machine Learning Containers for Jetson and JetPack 4.4.
* [jetson\_stats](https://github.com/rbonghi/jetson_stats) ⭐ 2,609 | 🐛 51 | 🌐 Python | 📅 2026-08-09 - A package to monitoring and control your NVIDIA Jetson (Xavier NX, Nano, AGX Xavier, TX1, TX2) Works with all NVIDIA Jetson ecosystem.
* [Jailhouse](https://github.com/siemens/jailhouse) ⭐ 1,952 | 🐛 0 | 🌐 C | 📅 2024-05-18 - Jailhouse is a partitioning Hypervisor based on Linux.
* [fusesoc](https://github.com/olofk/fusesoc) ⭐ 1,451 | 🐛 155 | 🌐 Python | 📅 2026-08-11 - Package manager and build abstraction tool for FPGA/ASIC development.
* [acrn-hypervisor](https://github.com/projectacrn/acrn-hypervisor) ⭐ 1,293 | 🐛 356 | 🌐 C | 📅 2026-04-06 - Defines a device hypervisor reference stack and an architecture for running multiple software subsystems, managed securely, on a consolidated system by means of a virtual machine manager.
* [nvidia-container-runtime](https://github.com/NVIDIA/nvidia-container-runtime/) ⚠️ Archived - NVIDIA Container Runtime is a GPU aware container runtime, compatible with the Open Containers Initiative (OCI) specification used by Docker, CRI-O, and other popular container technologie.
* [meta-balena](https://github.com/balena-os/meta-balena) ⭐ 989 | 🐛 139 | 🌐 BitBake | 📅 2026-08-19 - Run Docker containers on embedded devices.
* [rosserial](https://github.com/ros-drivers/rosserial) ⭐ 549 | 🐛 215 | 🌐 C++ | 📅 2024-04-25 - A ROS client library for small, embedded devices, such as Arduino.
* [bitbake](https://github.com/openembedded/bitbake) ⭐ 528 | 🐛 17 | 🌐 Python | 📅 2026-08-18 - A generic task execution engine that allows shell and Python tasks to be run efficiently and in parallel while working within complex inter-task dependency constraints.
* [meta-ros](https://github.com/ros/meta-ros/tree/thud-draft) ⭐ 486 | 🐛 93 | 🌐 BitBake | 📅 2026-08-17 - OpenEmbedded Layer for ROS Applications.
* [OpenCR](https://github.com/ROBOTIS-GIT/OpenCR) ⭐ 428 | 🐛 16 | 🌐 C | 📅 2024-05-01 - Open-source Control Module for ROS.
* [qemu-xilinx](https://github.com/Xilinx/qemu) ⭐ 300 | 🐛 52 | 🌐 C | 📅 2026-08-17 - A fork of Quick EMUlator (QEMU) with improved support and modelling for the Xilinx platforms.
* [jetson\_easy](https://github.com/rbonghi/jetson_easy) ⭐ 300 | 🐛 5 | 🌐 Shell | 📅 2020-12-23 - Automatically script to setup and configure your NVIDIA Jetson.
* [vxworks7-ros2-build](https://github.com/Wind-River/vxworks7-ros2-build) ⭐ 118 | 🐛 8 | 🌐 Makefile | 📅 2026-07-28 - Build system to automate the build of VxWorks 7 and ROS2.
* [ros\_jetson\_stats](https://github.com/rbonghi/ros_jetson_stats) ⭐ 72 | 🐛 6 | 🌐 Python | 📅 2023-03-05 - The ROS jetson-stats wrapper. The status of your NVIDIA jetson in diagnostic messages.
* [docker-jetpack-sdk](https://github.com/trn84/docker-jetpack-sdk) ⭐ 10 | 🐛 0 | 🌐 Dockerfile | 📅 2020-04-21 -  Allows for usage of the NVIDIA JetPack SDK within a docker container for download, flashing, and install.
* [Yocto](https://git.yoctoproject.org/) - Produce tools and processes that enable the creation of Linux distributions for embedded software that are independent of the underlying architecture of the embedded hardware.
* [Automotive Graded Linux](https://www.automotivelinux.org/software) - A collaborative open source project that is bringing together automakers, suppliers and technology companies to build a Linux-based, open software platform for automotive applications that can serve as the de facto industry standard.
* [Xen](https://wiki.debian.org/Xen) - An open-source (GPL) type-1 or baremetal hypervisor.
* [QEMU](https://www.qemu.org/) - A generic and open source machine emulator and virtualizer.
* [micro-ros](https://micro-ros.github.io/) - The major changes compared to "regular" ROS 2 is that micro-ROS uses a Real-Time Operating System (RTOS) instead of Linux, and DDS for eXtremely Resource Constrained Environments.
* [Pressed](https://wiki.debian.org/DebianInstaller/Preseed) - Provides a way to set answers to questions asked during the installation process of debian, without having to manually enter the answers while the installation is running.

### Real-Time Kernel

* [ELISA](https://elisa.tech/) -  Project is to make it easier for companies to build and certify Linux-based safety-critical applications – systems whose failure could result in loss of human life, significant property damage or environmental damage.
* [PREEMPT\_RT kernel patch](https://wiki.linuxfoundation.org/realtime/documentation/start) - Aim of the PREEMPT\_RT kernel patch is to minimize the amount of kernel code that is non-preemptible.

## Network and Middleware

* [protobuf](https://github.com/protocolbuffers/protobuf) ⭐ 71,737 | 🐛 290 | 🌐 C++ | 📅 2026-08-19 - Google's data interchange format.
* [Fast-RTPS](https://github.com/eProsima/Fast-RTPS) ⭐ 2,879 | 🐛 127 | 🌐 C++ | 📅 2026-08-19 - A Protocol, which provides publisher-subscriber communications over unreliable transports such as UDP, as defined and maintained by the Object Management Group (OMG) consortium.
* [iceoryx](https://github.com/eclipse/iceoryx) ⭐ 2,155 | 🐛 260 | 🌐 C++ | 📅 2026-08-18 - An IPC middleware for POSIX-based systems.
* [cyclonedds](https://github.com/eclipse-cyclonedds/cyclonedds) ⭐ 1,323 | 🐛 314 | 🌐 C | 📅 2026-08-18 - Eclipse Cyclone DDS is a very performant and robust open-source DDS implementation.
* [rosbridge\_suite](https://github.com/RobotWebTools/rosbridge_suite) ⭐ 1,237 | 🐛 30 | 🌐 Python | 📅 2026-08-17 - Provides a JSON interface to ROS, allowing any client to send JSON to publish or subscribe to ROS topics, call ROS services, and more.
* [ros1\_bridge](https://github.com/ros2/ros1_bridge) ⭐ 622 | 🐛 88 | 🌐 C++ | 📅 2025-11-17 - ROS 2 package that provides bidirectional communication between ROS 1 and ROS 2.
* [micro-ROS for Arduino](https://github.com/micro-ROS/micro_ros_arduino) ⭐ 573 | 🐛 76 | 🌐 C | 📅 2026-01-28 - A experimental micro-ROS library for baremetal projects based on Arduino IDE or Arduino CLI.
* [opensplice](https://github.com/ADLINK-IST/opensplice) ⭐ 267 | 🐛 67 | 🌐 C | 📅 2023-01-26 - Vortex OpenSplice Community Edition.
* [ros2arduino](https://github.com/ROBOTIS-GIT/ros2arduino) ⭐ 250 | 🐛 19 | 🌐 C | 📅 2021-02-02 - This library helps the Arduino board communicate with the ROS2 using XRCE-DDS.
* [ocpp](https://github.com/NewMotion/ocpp) ⚠️ Archived - The Open Charge Point Protocol (OCPP) is a network protocol for communication between electric vehicle chargers and a central backoffice system.
* [mqtt\_bridge](https://github.com/groove-x/mqtt_bridge) ⭐ 179 | 🐛 11 | 🌐 Python | 📅 2024-05-03 - Provides a functionality to bridge between ROS and MQTT in bidirectional.
* [realtime\_support](https://github.com/ros2/realtime_support) ⭐ 78 | 🐛 7 | 🌐 C++ | 📅 2026-07-15 - Minimal real-time testing utility for measuring jitter and latency.
* [performance\_test](https://github.com/ApexAI/performance_test) ⭐ 64 | 🐛 12 | 📅 2019-11-04 - Tool to test the performance of pub/sub based communication frameworks.
* [eCAL](https://github.com/continental/) - The enhanced communication abstraction layer (eCAL) is a middleware that enables scalable, high performance interprocess communication on a single computer node or between different nodes in a computer network.
* [AUTOSAR-Adaptive](https://github.com/UmlautSoftwareDevelopmentAccount/AUTOSAR-Adaptive) - The implementation of AUTOSAR Adaptive Platform based on the R19-11.

### Ethernet and Wireless Networking

* [termshark](https://github.com/gcla/termshark) ⭐ 9,959 | 🐛 50 | 🌐 Go | 📅 2024-04-30 - A terminal UI for tshark, inspired by Wireshark.
* [iperf](https://github.com/esnet/iperf) ⭐ 8,701 | 🐛 237 | 🌐 C | 📅 2026-07-10 - A TCP, UDP, and SCTP network bandwidth measurement tool.
* [openwifi](https://github.com/open-sdr/openwifi) ⭐ 4,758 | 🐛 93 | 🌐 C | 📅 2026-08-14 - Linux mac80211 compatible full-stack IEEE802.11/Wi-Fi design based on Software Defined Radio.
* [nethogs](https://github.com/raboof/nethogs) ⭐ 3,681 | 🐛 104 | 🌐 C++ | 📅 2026-07-23 - It groups bandwidth by process.
* [pyshark](https://github.com/KimiNewt/pyshark) ⭐ 2,493 | 🐛 144 | 🌐 Python | 📅 2026-03-22 - Python wrapper for tshark, allowing python packet parsing using wireshark dissectors.
* [tcpreplay](https://github.com/appneta/tcpreplay) ⭐ 1,344 | 🐛 0 | 🌐 C | 📅 2026-08-15 - Pcap editing and replay tools.
* [wavemon](https://github.com/uoaerg/wavemon) ⭐ 1,226 | 🐛 6 | 🌐 C | 📅 2026-06-29 - An ncurses-based monitoring application for wireless network devices.
* [SOES](https://github.com/OpenEtherCATsociety/SOES) ⭐ 833 | 🐛 32 | 🌐 C | 📅 2025-04-08 - SOES is an EtherCAT slave stack written in C.
* [ptpd](https://github.com/ptpd/ptpd) ⭐ 575 | 🐛 77 | 🌐 C | 📅 2022-09-05 - PTP daemon (PTPd) is an implementation the Precision Time Protocol (PTP) version 2 as defined by 'IEEE Std 1588-2008'. PTP provides precise time coordination of Ethernet LAN connected computers.
* [pingtop](https://github.com/laixintao/pingtop) ⭐ 537 | 🐛 4 | 🌐 Python | 📅 2026-07-13 - Ping multiple servers and show results in a top-like terminal UI.
* [udpreplay](https://github.com/rigtorp/udpreplay) ⭐ 290 | 🐛 4 | 🌐 C++ | 📅 2023-12-07 - Replay UDP packets from a pcap file.
* [ros\_ethercat](https://github.com/shadow-robot/ros_ethercat) ⭐ 111 | 🐛 13 | 🌐 C++ | 📅 2025-10-02 - This is a reimplementation of the main loop of pr2\_ethercat without dependencies on PR2 software.
* [wireless](https://github.com/clearpathrobotics/wireless) ⭐ 27 | 🐛 1 | 🌐 C++ | 📅 2026-07-17 - Making info about wireless networks available to ROS.
* [netplan](https://netplan.io/) - Simply create a YAML description of the required network interfaces and what each should be configured to do.
* [airalab](https://github.com/airalab) -  AIRA is reference Robonomics network client for ROS-enabled cyber-physical systems.
* [rdbox](https://github.com/rdbox-intec/rdbox) - RDBOX is a IT infrastructure for ROS robots.

### Controller Area Network

* [awesome CAN](https://github.com/iDoka/awesome-canbus) ⭐ 3,420 | 🐛 6 | 📅 2026-08-07 -  A curated list of awesome CAN bus tools, hardware and resources.
* [opendbc](https://github.com/commaai/opendbc) ⭐ 3,346 | 🐛 333 | 🌐 Python | 📅 2026-08-17 - The project to democratize access to the decoder ring of your car.
* [can-utils](https://github.com/linux-can/can-utils) ⭐ 2,905 | 🐛 62 | 🌐 C | 📅 2026-05-12 - Linux-CAN / SocketCAN user space applications.
* [cantools](https://github.com/eerimoq/cantools) ⭐ 2,269 | 🐛 127 | 🌐 Python | 📅 2026-08-17 - CAN BUS tools in Python 3.
* [AndrOBD](https://github.com/fr3ts0n/AndrOBD) ⭐ 2,068 | 🐛 71 | 🌐 Java | 📅 2026-08-19 - Android OBD diagnostics with any ELM327 adapter.
* [CANopenNode](https://github.com/CANopenNode/CANopenNode) ⭐ 1,978 | 🐛 114 | 🌐 C | 📅 2026-07-10 - The internationally standardized (EN 50325-4) (CiA301) CAN-based higher-layer protocol for embedded control system.
* [ddt4all](https://github.com/cedricp/ddt4all) ⭐ 1,810 | 🐛 1 | 🌐 Python | 📅 2026-07-14 - DDT4All is a tool to create your own ECU parameters screens and connect to a CAN network with a cheap ELM327 interface.
* [SavvyCAN](https://github.com/collin80/SavvyCAN) ⭐ 1,770 | 🐛 283 | 🌐 C++ | 📅 2026-05-15 - A Qt5 based cross platform tool which can be used to load, save, and capture canbus frames.
* [python-can](https://github.com/hardbyte/python-can) ⭐ 1,584 | 🐛 269 | 🌐 Python | 📅 2026-07-01 - The can package provides controller area network support for Python developers.
* [CANdevStudio](https://github.com/GENIVI/CANdevStudio) ⭐ 1,141 | 🐛 37 | 🌐 C++ | 📅 2025-07-21 -  CANdevStudio aims to be cost-effective replacement for CAN simulation software. It can work with variety of CAN hardware interfaces.
* [canmatrix](https://github.com/ebroecker/canmatrix) ⭐ 1,086 | 🐛 20 | 🌐 Python | 📅 2026-08-17 - Converting CAN Database Formats .arxml .dbc .dbf .kcd.
* [Open-Vehicle-Monitoring-System-3](https://github.com/openvehicles/Open-Vehicle-Monitoring-System-3) ⭐ 840 | 🐛 209 | 🌐 C | 📅 2026-08-15 - The system provides live monitoring of vehicle metrics like state of charge, temperatures, tyre pressures and diagnostic fault conditions.
* [uds-c](https://github.com/openxc/uds-c) ⭐ 821 | 🐛 6 | 🌐 C | 📅 2021-08-16 - Unified Diagnostics Service (UDS) and OBD-II (On Board Diagnostics for Vehicles) C Library.
* [python-udsoncan](https://github.com/pylessard/python-udsoncan) ⭐ 723 | 🐛 9 | 🌐 Python | 📅 2026-08-09 - Python implementation of UDS (ISO-14229) standard.
* [canopen](https://github.com/christiansandberg/canopen) ⭐ 563 | 🐛 74 | 🌐 Python | 📅 2026-06-28 - A Python implementation of the CANopen standard. The aim of the project is to support the most common parts of the CiA 301 standard in a Pythonic interface.
* [autosar](https://github.com/cogu/autosar) ⭐ 501 | 🐛 3 | 🌐 Python | 📅 2026-08-18 - A set of python modules for working with AUTOSAR XML files.
* [ros\_canopen](https://github.com/ros-industrial/ros_canopen) ⭐ 376 | 🐛 74 | 🌐 C++ | 📅 2025-04-14 - CANopen driver framework for ROS.
* [libuavcan](https://github.com/UAVCAN/libuavcan) ⭐ 327 | 🐛 21 | 🌐 C++ | 📅 2025-12-17 - An open lightweight protocol designed for reliable communication in aerospace and robotic applications over robust vehicular networks such as CAN bus.
* [cabana](https://github.com/commaai/cabana) ⚠️ Archived - CAN visualizer and DBC maker.
* [kvaser\_interface](https://github.com/astuff/kvaser_interface) ⭐ 90 | 🐛 5 | 🌐 C++ | 📅 2024-01-16 - This package was developed as a standardized way to access Kvaser CAN devices from ROS.
* [decanstructor](https://github.com/JWhitleyAStuff/decanstructor) ⭐ 36 | 🐛 7 | 🌐 C++ | 📅 2023-07-05 - The definitive ROS CAN analysis tool.

### Sensor and Acuator Interfaces

* [Tesla-API](https://github.com/timdorr/tesla-api) ⭐ 2,062 | 🐛 23 | 🌐 Ruby | 📅 2026-03-04 - Provides functionality to monitor and control the Model S (and future Tesla vehicles) remotely.
* [velodyne](https://github.com/ros-drivers/velodyne) ⭐ 722 | 🐛 104 | 🌐 C++ | 📅 2025-08-28 - A collection of ROS packages supporting Velodyne high definition 3D LIDARs.
* [ublox](https://github.com/KumarRobotics/ublox) ⭐ 535 | 🐛 122 | 🌐 C++ | 📅 2025-09-26 - Provides support for u-blox GPS receivers.
* [ouster\_example](https://github.com/ouster-lidar/ouster_example) ⭐ 523 | 🐛 76 | 🌐 C++ | 📅 2026-08-13 - Sample code for connecting to and configuring the OS1, reading and visualizing data, and interfacing with ROS.
* [livox\_ros\_driver](https://github.com/Livox-SDK/livox_ros_driver) ⭐ 499 | 🐛 85 | 🌐 C++ | 📅 2024-01-25 - A new ROS package, specially used to connect LiDAR products produced by Livox.
* [pymmw](https://github.com/m6c7l/pymmw) ⭐ 348 | 🐛 15 | 🌐 Python | 📅 2021-11-11 - This is a toolbox composed of Python scripts to interact with TI's evaluation module (BoosterPack) for the IWR1443 mmWave sensing device.
* [ti\_mmwave\_rospkg](https://github.com/radar-lab/ti_mmwave_rospkg) ⭐ 313 | 🐛 30 | 🌐 C++ | 📅 2024-03-01 - TI mmWave radar ROS driver (with sensor fusion and hybrid).
* [flirpy](https://github.com/LJMUAstroecology/flirpy) ⭐ 240 | 🐛 34 | 🌐 Python | 📅 2026-07-23 - A Python library to interact with FLIR thermal imaging cameras and images.
* [crazyflie\_ros](https://github.com/whoenig/crazyflie_ros) ⚠️ Archived - ROS Driver for Bitcraze Crazyflie.
* [pylon-ros-camera](https://github.com/basler/pylon-ros-camera) ⭐ 195 | 🐛 21 | 🌐 C++ | 📅 2026-07-30 - The official pylon ROS driver for Basler GigE Vision and USB3 Vision cameras.
* [novatel\_gps\_driver](https://github.com/swri-robotics/novatel_gps_driver) ⭐ 175 | 🐛 31 | 🌐 C++ | 📅 2026-06-08 - ROS driver for NovAtel GPS / GNSS receivers.
* [ros2\_intel\_realsense](https://github.com/intel/ros2_intel_realsense) ⚠️ Archived - These are packages for using Intel RealSense cameras (D400 series) with ROS2.
* [ros2\_ouster\_drivers](https://github.com/ros-drivers/ros2_ouster_drivers) ⭐ 149 | 🐛 23 | 🌐 C++ | 📅 2024-08-23 - These are an implementation of ROS2 drivers for the Ouster OS-1 3D lidars.
* [ros\_astra\_camera](https://github.com/orbbec/ros_astra_camera) ⭐ 128 | 🐛 80 | 🌐 C++ | 📅 2025-06-05 - A ROS driver for Orbbec 3D cameras.
* [pointgrey\_camera\_driver](https://github.com/ros-drivers/pointgrey_camera_driver) ⭐ 127 | 🐛 80 | 🌐 C++ | 📅 2022-01-31 - ROS driver for Pt. Grey cameras, based on the official FlyCapture2 SDK.
* [ifm3d](https://github.com/ifm/ifm3d) ⭐ 116 | 🐛 6 | 🌐 C++ | 📅 2026-08-17 - Library and Utilities for working with ifm pmd-based 3D ToF Cameras.
* [jetson\_csi\_cam](https://github.com/peter-moran/jetson_csi_cam) ⭐ 116 | 🐛 13 | 🌐 CMake | 📅 2020-07-12 - A ROS package making it simple to use CSI cameras on the Nvidia Jetson TK1, TX1, or TX2 with ROS.
* [ethz\_piksi\_ros](https://github.com/ethz-asl/ethz_piksi_ros) ⭐ 90 | 🐛 13 | 🌐 C++ | 📅 2023-04-18 -  Contains (python) ROS drivers, tools, launch files, and wikis about how to use Piksi Real Time Kinematic (RTK) GPS device in ROS.
* [sick\_safetyscanners](https://github.com/SICKAG/sick_safetyscanners) ⭐ 66 | 🐛 18 | 🌐 C++ | 📅 2024-06-19 - A ROS Driver which reads the raw data from the SICK Safety Scanners and publishes the data as a laser\_scan msg.
* [bosch\_imu\_driver](https://github.com/mdrwiega/bosch_imu_driver) ⭐ 60 | 🐛 3 | 🌐 Python | 📅 2021-04-21 - A driver for the sensor IMU Bosch BNO055. It was implemented only the UART communication interface (correct sensor mode should be selected).
* [TauLidarCamera](https://github.com/OnionIoT/tau-LiDAR-camera) ⭐ 36 | 🐛 8 | 🌐 Python | 📅 2023-08-23 - The host-side API for building applications with the Tau LiDAR Camera.
* [pacmod3](https://github.com/astuff/pacmod3) ⭐ 30 | 🐛 11 | 🌐 C++ | 📅 2023-06-29 - This ROS node is designed to allow the user to control a vehicle with the PACMod drive-by-wire system, board revision 3.
* [cepton\_sdk\_redist](https://github.com/ceptontech/cepton_sdk_redist/) ⭐ 24 | 🐛 17 | 🌐 Python | 📅 2025-07-20 - Provides ROS support for Cepton LiDAR.
* [blickfeld-scanner-lib](https://github.com/Blickfeld/blickfeld-scanner-lib) ⭐ 22 | 🐛 1 | 🌐 C++ | 📅 2023-01-17 - Cross-platform library to communicate with LiDAR devices of the Blickfeld GmbH.
* [nerian\_stereo](https://github.com/nerian-vision/nerian_stereo) ⭐ 8 | 🐛 0 | 🌐 C++ | 📅 2024-01-23 - ROS node for Nerian's SceneScan and SP1 stereo vision sensors.
* [spot\_ros](https://github.com/clearpathrobotics/spot_ros) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-04-01 - ROS Driver for Spot.
* [sick\_scan](https://github.com/SICKAG/sick_scan) - This stack provides a ROS2 driver for the SICK TiM series of laser scanners.
* [oxford\_gps\_eth](https://bitbucket.org/DataspeedInc/oxford_gps_eth/) - Ethernet interface to OxTS GPS receivers using the NCOM packet structure.

## Security

* [Vault](https://github.com/hashicorp/vault) ⭐ 36,140 | 🐛 1,425 | 🌐 Go | 📅 2026-08-19 - A tool for securely accessing secrets. A secret is anything that you want to tightly control access to, such as API keys, passwords, certificates, and more.
* [How-to-Secure-A-Linux-Server](https://github.com/imthenachoman/How-To-Secure-A-Linux-Server) ⭐ 30,295 | 🐛 34 | 📅 2026-07-13 - An evolving how-to guide for securing a Linux server.
* [fail2ban](https://github.com/fail2ban/fail2ban) ⭐ 18,418 | 🐛 272 | 🌐 Python | 📅 2026-08-18 - Daemon to ban hosts that cause multiple authentication errors.
* [lynis](https://github.com/CISOfy/lynis) ⭐ 16,178 | 🐛 218 | 🌐 Shell | 📅 2026-08-05 - Security auditing tool for Linux, macOS, and UNIX-based systems. Assists with compliance testing (HIPAA/ISO27001/PCI DSS) and system hardening.
* [OpenVPN](https://github.com/OpenVPN/openvpn) ⭐ 14,400 | 🐛 223 | 🌐 C | 📅 2026-08-19 - An open source VPN daemon.
* [bandit](https://github.com/PyCQA/bandit) ⭐ 8,224 | 🐛 259 | 🌐 Python | 📅 2026-08-04 - A tool designed to find common security issues in Python code.
* [Firejail](https://github.com/netblue30/firejail) ⭐ 7,601 | 🐛 525 | 🌐 C | 📅 2026-08-17 - A SUID sandbox program that reduces the risk of security breaches by restricting the running environment of untrusted applications using Linux namespaces, seccomp-bpf and Linux capabilities.
* [gopass](https://github.com/gopasspw/gopass) ⭐ 7,095 | 🐛 97 | 🌐 Go | 📅 2026-08-17 - A password manager for the command line written in Go.
* [vulscan](https://github.com/scipag/vulscan) ⭐ 3,779 | 🐛 7 | 🌐 Lua | 📅 2026-02-06 - Advanced vulnerability scanning with Nmap NSE.
* [OpenTitan](https://github.com/lowRISC/opentitan) ⭐ 3,599 | 🐛 2,056 | 🌐 SystemVerilog | 📅 2026-08-19 - Will make the silicon Root of Trust design and implementation more transparent, trustworthy, and secure for enterprises, platform providers, and chip manufacturers. OpenTitan is administered by lowRISC CIC as a collaborative project to produce high quality, open IP for instantiation as a full-featured product.
* [nmap-vulners](https://github.com/vulnersCom/nmap-vulners) ⭐ 3,402 | 🐛 0 | 🌐 Lua | 📅 2026-08-18 - NSE script based on Vulners.com API.
* [openfortivpn](https://github.com/adrienverge/openfortivpn) ⭐ 3,390 | 🐛 141 | 🌐 Perl | 📅 2026-08-17 - A client for PPP+SSL VPN tunnel services and compatible with Fortinet VPNs.
* [wolfssl](https://github.com/wolfSSL/wolfssl) ⭐ 2,911 | 🐛 188 | 🌐 C | 📅 2026-08-19 - A small, fast, portable implementation of TLS/SSL for embedded devices to the cloud.
* [brutespray](https://github.com/x90skysn3k/brutespray) ⭐ 2,520 | 🐛 17 | 🌐 Go | 📅 2026-08-17 - Automatically attempts default creds on found services.
* [WireGuard](https://github.com/WireGuard/WireGuard) ⚠️ Archived - WireGuard is a novel VPN that runs inside the Linux Kernel and utilizes state-of-the-art cryptography.
* [hardening](https://github.com/konstruktoid/hardening) ⭐ 1,854 | 🐛 6 | 🌐 Shell | 📅 2026-08-17 - A quick way to make a Ubuntu server a bit more secure.
* [openscap](https://github.com/OpenSCAP/openscap) ⭐ 1,799 | 🐛 61 | 🌐 XSLT | 📅 2026-08-13 - The oscap program is a command line tool that allows users to load, scan, validate, edit, and export SCAP documents.
* [Security-Enhanced Linux](https://github.com/SELinuxProject/selinux) ⭐ 1,618 | 🐛 17 | 🌐 C | 📅 2026-08-17 - A Linux kernel security module that provides a mechanism for supporting access control security policies, including mandatory access controls (MAC).
* [Passbolt](https://github.com/passbolt/passbolt_docker) ⭐ 1,108 | 🐛 9 | 🌐 Ruby | 📅 2026-08-12 - Passbolt is a free and open source password manager that allows team members to store and share credentials securely.
* [legion](https://github.com/GoVanguard/legion) ⚠️ Archived - An open source, easy-to-use, super-extensible and semi-automated network penetration testing framework that aids in discovery, reconnaissance and exploitation of information systems.
* [CANalyzat0r](https://github.com/schutzwerk/CANalyzat0r) ⭐ 793 | 🐛 3 | 🌐 Python | 📅 2022-02-21 - Security analysis toolkit for proprietary car protocols.
* [ssh-auditor](https://github.com/ncsa/ssh-auditor) ⭐ 620 | 🐛 5 | 🌐 Go | 📅 2023-12-18 - Scans for weak ssh passwords on your network.
* [owasp-threat-dragon-desktop](https://github.com/mike-goodwin/owasp-threat-dragon-desktop) ⭐ 591 | 🐛 78 | 🌐 CSS | 📅 2026-01-29 - Threat Dragon is a free, open-source, cross-platform threat modeling application including system diagramming and a rule engine to auto-generate threats/mitigations.
* [RVD](https://github.com/aliasrobotics/RVD) ⭐ 241 | 🐛 227 | 🌐 Python | 📅 2026-07-14 - Robot Vulnerability Database. Community-contributed archive of robot vulnerabilities and weaknesses.
* [RSF](https://github.com/aliasrobotics/RSF) ⭐ 97 | 🐛 1 | 📅 2026-07-14 - Robot Security Framework (RSF) is a standardized methodology to perform security assessments in robotics.
* [DependencyCheck](https://github.com/jeremylong/DependencyCheck) ⚠️ Archived - A software composition analysis utility that detects publicly disclosed vulnerabilities in application dependencies.
* [launch\_ros\_sandbox](https://github.com/ros-tooling/launch_ros_sandbox) ⚠️ Archived - Can define launch files running nodes in restrained environments, such as Docker containers or separate user accounts with limited privileges.
* [ros2\_dds\_security](http://design.ros2.org/articles/ros2_dds_security.html) - Adding security enhancements by defining a Service Plugin Interface (SPI) architecture, a set of builtin implementations of the SPIs, and the security model enforced by the SPIs.
* [pass](https://www.passwordstore.org/) - The standard unix password manager.

## Datasets

* [awesome-satellite-imagery-datasets](https://github.com/chrieke/awesome-satellite-imagery-datasets) ⚠️ Archived - List of satellite image training datasets with annotations for computer vision and deep learning.
* [BlenderProc](https://github.com/DLR-RM/BlenderProc) ⭐ 3,678 | 🐛 116 | 🌐 Python | 📅 2026-01-20 - A procedural Blender pipeline for photorealistic training image generation.
* [waymo-open-dataset](https://github.com/waymo-research/waymo-open-dataset) ⭐ 3,390 | 🐛 465 | 🌐 Python | 📅 2026-01-08 - The Waymo Open Dataset is comprised of high-resolution sensor data collected by Waymo self-driving cars in a wide variety of conditions.
* [nuscenes-devkit](https://github.com/nutonomy/nuscenes-devkit) ⭐ 2,794 | 🐛 32 | 🌐 Python | 📅 2026-08-06 - The devkit of the nuScenes dataset.
* [Objectron](https://github.com/google-research-datasets/Objectron/) ⭐ 2,348 | 🐛 31 | 🌐 Jupyter Notebook | 📅 2026-03-06 - A collection of short, object-centric video clips, which are accompanied by AR session metadata that includes camera poses, sparse point-clouds and characterization of the planar surfaces in the surrounding environment.
* [sentinelsat](https://github.com/sentinelsat/sentinelsat) ⚠️ Archived - Search and download Copernicus Sentinel satellite images.
* [argoverse-api](https://github.com/argoai/argoverse-api) ⭐ 932 | 🐛 71 | 🌐 Python | 📅 2023-12-15 - Official GitHub repository for Argoverse dataset.
* [dataset-api](https://github.com/ApolloScapeAuto/dataset-api) ⭐ 619 | 🐛 87 | 🌐 Jupyter Notebook | 📅 2026-04-04 - This is a repo of toolkit for ApolloScape Dataset, CVPR 2019 Workshop on Autonomous Driving Challenge and ECCV 2018 challenge.
* [DDAD](https://github.com/TRI-ML/DDAD) ⭐ 560 | 🐛 17 | 🌐 Python | 📅 2021-05-12 - A new autonomous driving benchmark from TRI (Toyota Research Institute) for long range (up to 250m) and dense depth estimation in challenging and diverse urban conditions.
* [awesome-robotics-datasets](https://github.com/sunglok/awesome-robotics-datasets) ⭐ 516 | 🐛 3 | 📅 2021-08-26 - A collection of useful datasets for robotics and computer vision.
* [KITTI-360](https://github.com/autonomousvision/kitti360Scripts) ⭐ 445 | 🐛 58 | 🌐 Python | 📅 2025-08-14 -  This large-scale dataset contains 320k images and 100k laser scans in a driving distance of 73.7km.
* [racetrack-database](https://github.com/TUMFTM/racetrack-database) ⭐ 295 | 🐛 0 | 📅 2021-09-18 - Contains center lines (x- and y-coordinates), track widths and race lines for over 20 race tracks (mainly F1 and DTM) all over the world.
* [pandaset-devkit](https://github.com/scaleapi/pandaset-devkit) ⭐ 279 | 🐛 57 | 🌐 Jupyter Notebook | 📅 2023-08-14 - Public large-scale dataset for autonomous driving provided by Hesai & Scale.
* [utbm\_robocar\_dataset](https://github.com/epan-utbm/utbm_robocar_dataset) ⭐ 246 | 🐛 8 | 🌐 C++ | 📅 2024-07-28 - EU Long-term Dataset with Multiple Sensors for Autonomous Driving.
* [DBNet](https://github.com/driving-behavior/DBNet) ⭐ 221 | 🐛 7 | 🌐 Python | 📅 2019-03-20 - A Large-Scale Dataset for Driving Behavior Learning.
* [holicity](https://github.com/zhou13/holicity) ⭐ 95 | 🐛 6 | 🌐 Python | 📅 2022-01-20 - A City-Scale Data Platform for Learning Holistic 3D Structures.
* [waymo\_ros](https://github.com/YonoHub/waymo_ros) ⭐ 11 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2020-07-05 - This is a ROS package to connect Waymo open dataset to ROS.
* [Papers With Code](https://www.paperswithcode.com/datasets) - Thousands of machine learning datasets provided by Papers With Code.
* [Ford Autonomous Vehicle Dataset](https://avdata.ford.com/home/default.aspx) - Ford presents a challenging multi-agent seasonal dataset collected by a fleet of Ford autonomous vehicles at different days and times.
* [a2d2\_to\_ros](https://gitlab.com/MaplessAI/external/a2d2_to_ros) - Utilities for converting A2D2 data sets to ROS bags.
* [adas-dataset-form](https://www.flir.com/oem/adas/adas-dataset-form/) - Thermal Dataset for Algorithm Training.
* [h3d](https://usa.honda-ri.com/h3d) - The H3D is a large scale full-surround 3D multi-object detection and tracking dataset from Honda.
* [Mapillary Vistas Dataset](https://www.mapillary.com/dataset/vistas) - A diverse street-level imagery dataset with pixel‑accurate and instance‑specific human annotations for understanding street scenes around the world.
* [TensorFlow Datasets](https://www.tensorflow.org/datasets/catalog/overview) - TensorFlow Datasets provides many public datasets as tf.data.Datasets.
* [Atlatec Sample Map Data](https://www.atlatec.de/getsampledata.html) - 3D map for autonomous driving and simulation created from nothing but two cameras and GPS in downtown San Francisco.
* [Lyft Level 5 Dataset](https://self-driving.lyft.com/level5/data/) - Level 5 is developing a self-driving system for the Lyft network. We're collecting and processing data from our autonomous fleet and sharing it with you.
* [UTD19](https://utd19.ethz.ch/) - Largest multi-city traffic dataset publically available.
* [ASTYX HIRES2019 DATASET](http://www.pinchofintelligence.com/visualising-lidar-and-radar-in-virtual-reality/) - Automotive Radar Dataset for Deep Learning Based 3D Object Detection.
* [ONCE dataset](https://once-for-auto-driving.github.io/index.html) - A large-scale autonomous driving dataset with 2D&3D object annotations.

## Footnotes

Thanks to the team of [xpp](http://wiki.ros.org/xpp) for creating this awesome GIF we use.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
