# Awesome uno platform with stars

<div align="center">
	<img width="160" src="media/logo.png" alt="Uno Platform">
	<h1>Awesome Uno Platform</h1>
	<a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
</div>

[Uno Platform](https://platform.uno/) is an open-source UI Platform for building single-codebase .NET applications for Windows, iOS, Android, WebAssembly, macOS, and Linux.

This is a list of **awesome resources** for users of Uno Platform. **If you find the list helpful, please make sure to ⭐ star it!**

## Contents

* [General](#general)
* [Community](#community)
* [Repositories](#repositories)
* [Tools](#tools)
  * [IDE and Design](#ide-and-design)
  * [AI](#ai)
  * [Build and Deployment](#build-and-deployment)
  * [Testing](#testing)
* [Libraries](#libraries)
  * [Toolkits](#toolkits)
  * [Controls](#controls)
  * [Graphics](#graphics)
  * [Media](#media)
  * [MVVM](#mvvm)
  * [Dependency Injection](#dependency-injection)
  * [Integrations](#integrations)
  * [Compatibility](#compatibility)
* [Samples](#samples)
* [Live apps](#live-apps)
* [Open-source apps](#open-source-apps)
* [Games](#games)
* [Case Studies](#case-studies)
* [Blogs](#blogs)
* [Articles](#articles)
* [Courses and Tutorials](#courses-and-tutorials)
* [Live coding](#live-coding)
* [Talks](#talks)
* [Videos](#videos)
* [Podcasts](#podcasts)
* [Books](#books)

## General

* [Uno Platform Website](https://platform.uno/platforms/) - Supported platforms, features and product overview.
* [Uno Platform Documentation](https://platform.uno/docs/articles/intro.html) - Guides, tutorials and API reference.
* [Live Wizard](https://new.platform.uno/) - Browser-based wizard that configures a new project and generates the matching `dotnet new` command.
* [Get Started Guide](https://platform.uno/docs/articles/get-started.html) - Environment setup for each OS, IDE and AI agent, leading into the first-app tutorials.

## Community

* [Discord](https://platform.uno/discord) - Official chat server for questions, help and announcements.
* [GitHub Discussions](https://github.com/unoplatform/uno/discussions) ⭐ 10,128 | 🐛 2,444 | 🌐 C# | 📅 2026-11-20 - Q\&A, ideas and show-and-tell forum on the main repository.
* [Stack Overflow](https://stackoverflow.com/questions/tagged/uno-platform) - Q\&A tag for framework and tooling questions.
* [X (Twitter)](https://x.com/UnoPlatform) - Official account for release news and community highlights.
* [LinkedIn](https://www.linkedin.com/company/uno-platform/) - Official company page with product and release updates.
* [r/unoplatform](https://www.reddit.com/r/unoplatform/) - Official subreddit for news, tutorials and questions.
* [Uno Platform Newsletter](https://platform.uno/newsletter-sign-up/) - Email newsletter with release news, blog posts, tutorials and Uno Tech Bites videos.

## Repositories

* [Uno Platform](https://github.com/unoplatform/uno) ⭐ 10,128 | 🐛 2,444 | 🌐 C# | 📅 2026-11-20 - Main repository of Uno Platform, including the full API surface of UWP/WinUI, the best place to submit issues and contribute.
* [Uno Samples](https://github.com/unoplatform/Uno.Samples) ⭐ 265 | 🐛 146 | 🌐 C# | 📅 2026-11-20 - A growing collection of code samples and snippets.
* [Uno Themes](https://github.com/unoplatform/Uno.Themes) ⭐ 186 | 🐛 216 | 🌐 C# | 📅 2026-11-20 - Material and Cupertino theme library for Uno Platform apps. In addition, includes advanced controls based on Android/iOS developer guidelines.
* [Uno Gallery](https://github.com/unoplatform/Uno.Gallery) ⭐ 171 | 🐛 164 | 🌐 C# | 📅 2026-11-12 - Controls and API gallery app. Includes live examples of most built-in controls and features along with easy to use code snippets.
* [Uno Toolkit](https://github.com/unoplatform/uno.toolkit.ui) ⭐ 109 | 🐛 241 | 🌐 C# | 📅 2026-11-20 - Multiplatform-first UI component library to speed up application development. Also provides Material and Cupertino styles for the included components.
* [Uno Core](https://github.com/unoplatform/Uno.Core) ⭐ 41 | 🐛 12 | 🌐 C# | 📅 2026-11-03 - Provides a set of reusable utilities and helpers. Used by the main Uno Platform repository.
* [Uno UI Test](https://github.com/unoplatform/Uno.UITest) ⭐ 12 | 🐛 24 | 🌐 C# | 📅 2026-10-13 - Xamarin.UITest-style UI testing, using Selenium for WebAssembly and Xamarin.UITest for Android and iOS.

## Tools

### IDE and Design

* [XAML Styler](https://github.com/Xavalon/XamlStyler) ⭐ 1,385 | 🐛 124 | 🌐 C# | 📅 2026-04-14 - XAML formatter for Visual Studio, Rider and the command line, used to enforce markup style in the official repositories.
* [DevToolsUno](https://github.com/wieslawsoltes/DevToolsUno) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2026-08-18 - In-app diagnostics for inspecting the live visual tree, bindings, resources, styles, events and memory.
* [Uno Platform Extension for Visual Studio](https://marketplace.visualstudio.com/items?itemName=unoplatform.uno-platform-addin-2022) - Project templates, Hot Reload and Hot Design tooling for Visual Studio 2022 and 2026.
* [Uno Platform Extension for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=unoplatform.vscode) - Adds a range of productivity boosters to Visual Studio Code, including XAML IntelliSense, Hot Reload, and mobile target debugging support.
* [Uno Platform for Figma](https://www.figma.com/community/plugin/1045528009520465828/uno-platform-figma-to-c-or-xaml) - Figma plugin that generates responsive XAML or C# Markup from high-fidelity designs.
* [Uno Material Toolkit](https://www.figma.com/community/file/1110792522046146058/Uno-Platform-Material-Toolkit) - Figma file to use with the Figma plugin.
* [Uno Platform Studio](https://platform.uno/studio/) - Productivity suite bundling Hot Reload, Hot Design, design-to-code, MCP servers and an AI agent, usable from any IDE or OS.
* [Hot Design](https://platform.uno/hot-design/) - Agentic visual designer that turns the running app into an editable design surface, from Visual Studio, VS Code or Rider.
* [Hot Reload](https://platform.uno/hot-reload/) - Applies XAML and C# changes to the running app on every target without rebuilding, free in the Community tier.
* [Uno Platform Plugin for JetBrains Rider](https://plugins.jetbrains.com/plugin/24653-uno-platform) - Rider plugin adding project templates, Hot Reload and Hot Design support.

### AI

* [Uno Platform Studio Agent Plugin](https://github.com/unoplatform/studio) ⭐ 11 | 🐛 50 | 🌐 C# | 📅 2026-11-19 - Agent plugin with an app-building agent, topic skills (MVUX, navigation, Toolkit, themes, testing) and Hot Reload hooks for Claude Code, GitHub Copilot and Codex.
* [dotnet-agentic-engineering (dna)](https://github.com/VincentH-Net/dotnet-agentic-engineering) ⭐ 10 | 🐛 2 | 🌐 C# | 📅 2026-11-17 - Agent directives, skills and tooling that detect a repo's stack (MVUX or MVVM, C# Markup, design system, SDK version) and install a matching skill set.
* [Uno Platform Skills](https://github.com/noknowscode/UnoPlatformSkills) ⭐ 5 | 🐛 0 | 📅 2026-04-07 - Claude Code skills covering MVUX, navigation, Toolkit, Material theming, C# Markup, WebAssembly and WPF migration.
* [Uno Platform MCP](https://platform.uno/mcp/) - Free remote MCP server that grounds AI agents in the current documentation and API references.
* [Uno App MCP](https://platform.uno/docs/articles/features/using-the-uno-mcps.html#app-mcp-local) - Local MCP server that lets AI agents inspect and drive a running app through its visual tree, properties, clicks, typing and screenshots.
* [Uno Platform Studio App](https://studio.platform.uno/) - Browser-based AI app builder (Pro) that generates a project from a prompt, previews it live and exports it to your IDE.
* [Uno DevServer CLI](https://www.nuget.org/packages/Uno.DevServer) - Dev Server CLI that registers the MCPs with AI agents, diagnoses the environment and drives a running app from scripts or CI.

### Build and Deployment

* [Velopack](https://github.com/velopack/velopack) ⭐ 2,484 | 🐛 59 | 🌐 C# | 📅 2026-11-16 - Installer and auto-update framework for desktop apps, with an official Uno sample and setup guide.
* [Uno.Wasm.Bootstrap](https://github.com/unoplatform/Uno.Wasm.Bootstrap) ⭐ 383 | 🐛 80 | 🌐 WebAssembly | 📅 2026-11-13 - MSBuild package that builds and hosts .NET code in the browser via WebAssembly, with AOT and PWA support.
* [DependencyPropertyGenerator](https://github.com/HavenDV/DependencyPropertyGenerator) ⭐ 155 | 🐛 4 | 🌐 C# | 📅 2026-11-16 - Source generator for dependency properties, routed events and weak events, with automatic Uno detection.
* [Uno.Check](https://github.com/unoplatform/uno.check) ⭐ 48 | 🐛 93 | 🌐 C# | 📅 2026-11-19 - CLI that checks and installs the SDKs, workloads and tooling needed for each target platform.
* [Uno.Templates and Uno.Sdk](https://github.com/unoplatform/uno.templates) ⭐ 29 | 🐛 117 | 🌐 C# | 📅 2026-11-20 - The `dotnet new` app and library templates plus the single-project MSBuild SDK they build on.
* [Uno.Resizetizer](https://github.com/unoplatform/uno.resizetizer) ⭐ 18 | 🐛 68 | 🌐 C# | 📅 2026-11-18 - Build-time generation of app icons, splash screens and scaled images from SVG or PNG sources.
* [Uno.XamlMerge.Task](https://github.com/unoplatform/uno.xamlmerge.task) ⭐ 7 | 🐛 8 | 🌐 C# | 📅 2026-11-11 - MSBuild task that merges a control library's resource dictionaries into a single file for faster resource lookup.

### Testing

* [Uno.UI.RuntimeTests.Engine](https://github.com/unoplatform/uno.ui.runtimetests.engine) ⭐ 9 | 🐛 30 | 🌐 C# | 📅 2026-11-19 - In-app MSTest runner for UI tests on devices, desktop and the browser, with NUnit reports and CI sharding.

## Libraries

### Toolkits

* [Windows Community Toolkit](https://github.com/CommunityToolkit/Windows) ⭐ 1,083 | 🐛 240 | 🌐 C# | 📅 2026-10-27 - Microsoft-backed collection of WinUI controls, helpers and extensions that ships builds for every target.
* [Uno Extensions](https://github.com/unoplatform/uno.extensions) ⭐ 101 | 🐛 411 | 🌐 C# | 📅 2026-11-19 - NuGet packages for navigation, DI, configuration, HTTP, localization and the MVUX reactive pattern.
* [CherylUI.Uno](https://github.com/kikipoulet/CherylUI.Uno) ⭐ 85 | 🐛 0 | 🌐 C# | 📅 2026-06-03 - Mobile-styled controls and styles ported from the CherylUI library.
* [dt (搬运工)](https://github.com/Daoting/dt) ⭐ 61 | 🐛 9 | 🌐 C# | 📅 2026-11-17 - Chinese-language framework for rapid line-of-business apps, with reusable client controls and backend microservices.
* [Flowery.Uno](https://github.com/tobitege/Flowery.Uno) ⭐ 16 | 🐛 5 | 🌐 C# | 📅 2026-11-16 - Over 100 DaisyUI-inspired themed controls, localized in 12 languages.
* [Telerik UI for Uno](https://github.com/unoplatform/Uno.Telerik.UI-For-UWP) ⭐ 15 | 🐛 0 | 🌐 C# | 📅 2025-03-24 - Community port of the open-source Telerik UI for UWP controls.
* [Uno.Fonts](https://github.com/unoplatform/uno.fonts) ⭐ 12 | 🐛 14 | 🌐 PowerShell | 📅 2026-11-03 - Font packages with Fluent and MDL2 icon fonts as drop-in Segoe replacements, plus Roboto, Open Sans and Inter.
* [Infragistics Ultimate UI for Uno Platform](https://github.com/Infragistics/uno-samples) ⭐ 5 | 🐛 6 | 🌐 C# | 📅 2026-11-20 - Commercial (beta) charts, data grid, geographic maps, gauges and dashboard components, with a samples browser.
* [MZikmund Toolkit](https://github.com/MartinZikmund/mzikmund-toolkit) ⭐ 1 | 🐛 62 | 🌐 C# | 📅 2026-11-08 - Reusable app services such as preferences storage and a ContentDialog coordinator, with a gallery sample app, by Martin Zikmund.

### Controls

* [ScottPlot](https://github.com/ScottPlot/ScottPlot) ⭐ 6,804 | 🐛 255 | 🌐 C# | 📅 2026-08-15 - Interactive plotting library built for large scientific and high-density datasets.
* [LiveCharts2](https://github.com/Live-Charts/LiveCharts2) ⭐ 5,511 | 🐛 52 | 🌐 C# | 📅 2026-11-19 - Interactive, animated charts, maps and gauges drawn with SkiaSharp.
* [Mapsui](https://github.com/Mapsui/Mapsui) ⭐ 1,582 | 🐛 160 | 🌐 C# | 📅 2026-11-17 - Map component with tile layers, vector data and touch interaction.
* [CSharpMath](https://github.com/verybadcat/CSharpMath) ⭐ 460 | 🐛 90 | 🌐 C# | 📅 2026-08-31 - LaTeX math typesetting and rendering, ported from iosMath.
* [WinUI.TableView](https://github.com/w-ahmad/WinUI.TableView) ⭐ 373 | 🐛 71 | 🌐 C# | 📅 2026-11-20 - Lightweight, fast DataGrid control with Excel-like column filtering, sorting, editing and export.
* [FluentIcons](https://github.com/davidxuang/FluentIcons) ⭐ 226 | 🐛 2 | 🌐 C# | 📅 2026-11-19 - Fluent UI System Icons as icon controls, icon sources and markup extensions.
* [WinUI.Dock](https://github.com/qian-o/WinUI.Dock) ⭐ 92 | 🐛 4 | 🌐 C# | 📅 2026-09-21 - Visual Studio-style docking controls, with limited floating-window support.
* [Broadside](https://github.com/michaelstonis/Broadside) ⭐ 81 | 🐛 42 | 🌐 C# | 📅 2026-11-20 - Fully managed PDF library for reading, writing, editing and rendering, with an embeddable viewer.
* [DesktopFlyouts](https://github.com/0x5bfa/DesktopFlyouts) ⭐ 49 | 🐛 5 | 🌐 C# | 📅 2026-11-19 - Desktop flyouts shown from tray icons or programmatically, including on Linux with X11.
* [RibbonSpace](https://github.com/wieslawsoltes/RibbonSpace) ⭐ 35 | 🐛 6 | 🌐 C# | 📅 2026-11-19 - Office-style ribbon with adaptive layouts, contextual tabs, backstage, Quick Access Toolbar and KeyTips.
* [Pysar](https://github.com/MriyaLab/Pysar) ⭐ 32 | 🐛 0 | 🌐 C# | 📅 2026-11-01 - Report engine for paginated documents with an in-app report view, PDF export, printing and sharing.
* [Uno Monaco Editor](https://github.com/unoplatform/uno.monaco.editor) ⭐ 21 | 🐛 1 | 🌐 C# | 📅 2026-11-12 - Monaco (VS Code) code editor control with language providers, diff view and two-way text binding for WebAssembly and desktop.
* [UnoEdit](https://github.com/lextudio/UnoEdit) ⭐ 10 | 🐛 0 | 🌐 C# | 📅 2026-08-06 - Code editor control with syntax highlighting, ported from AvalonEdit.
* [UnoKeyboard](https://github.com/mcNets/UnoKeyboard) ⭐ 9 | 🐛 1 | 🌐 C# | 📅 2026-01-31 - On-screen virtual keyboard for touch-screen desktop, Windows and WebAssembly apps.
* [UnoDock](https://github.com/wieslawsoltes/UnoDock) ⭐ 6 | 🐛 1 | 🌐 C# | 📅 2026-11-18 - IDE-style docking with documents, tool windows, auto-hide, floating windows and themes.
* [Uno ColorCode](https://github.com/unoplatform/Uno.ColorCode-Universal) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2026-11-12 - Syntax highlighting library that renders source code into a RichTextBlock or HTML.
* [ScreenKeyboard](https://github.com/wieslawsoltes/ScreenKeyboardControl) ⭐ 1 | 🐛 4 | 🌐 C# | 📅 2026-11-17 - Themable on-screen keyboard with glide typing, gestures, emoji and 90+ layouts.

### Graphics

* [SkiaSharp](https://github.com/mono/SkiaSharp) ⭐ 5,640 | 🐛 925 | 🌐 C# | 📅 2026-11-20 - Cross-platform 2D graphics API based on Google's Skia, with XAML canvas views.
* [Svg.Skia](https://github.com/wieslawsoltes/Svg.Skia) ⭐ 749 | 🐛 3 | 🌐 C# | 📅 2026-11-16 - SVG rendering library with animated SVG controls and inline SVG authoring in XAML.
* [ProGPU](https://github.com/wieslawsoltes/ProGPU) ⭐ 192 | 🐛 7 | 🌐 C# | 📅 2026-11-10 - WebGPU-based rendering, composition, vector and text engine with an embeddable host control.
* [Zenith.NET](https://github.com/qian-o/Zenith.NET) ⭐ 190 | 🐛 1 | 🌐 C# | 📅 2026-11-20 - GPU graphics and compute abstraction over DirectX 12, Metal and Vulkan, with a rendering view control.
* [Ab4d.SharpEngine](https://www.ab4d.com/SharpEngine.aspx) - Commercial cross-platform 3D rendering engine built on Vulkan, free for non-commercial open-source projects.
* [SKCanvasElement](https://platform.uno/docs/articles/controls/SKCanvasElement.html) - Hardware-accelerated SkiaSharp drawing hosted directly in the XAML visual tree.
* [GLCanvasElement](https://platform.uno/docs/articles/controls/GLCanvasElement.html) - OpenGL rendering through Silk.NET inside the XAML visual tree, with WebGL on WebAssembly.
* [Lottie Animations](https://platform.uno/docs/articles/features/Lottie.html) - Built-in Lottie playback through AnimatedVisualPlayer, rendered with Skottie or a managed engine.

### Media

* [LibVLCSharp](https://github.com/videolan/libvlcsharp) ⭐ 1,830 | 🐛 1 | 🌐 C# | 📅 2026-11-03 - VLC-based media playback bindings with a MediaPlayerElement control for Windows, Android and iOS.
* [VisioForge Media Framework](https://www.visioforge.com/) - Commercial SDKs for video capture, playback, editing and streaming, including a cross-platform video view control.

### MVVM

* [R3](https://github.com/Cysharp/R3) ⭐ 4,052 | 🐛 38 | 🌐 C# | 📅 2026-10-08 - Modern reimplementation of Reactive Extensions, with an extension package for dispatcher-timer and rendering-frame providers.
* [Shiny Mediator](https://github.com/shinyorg/mediator) ⭐ 55 | 🐛 0 | 🌐 C# | 📅 2026-11-14 - Mediator pattern library with app middleware for caching, offline, resilience and main-thread dispatch.
* [Microsoft.UI.Reactor for Uno](https://github.com/unoplatform/Uno.microsoft-ui-reactor) ⭐ 15 | 🐛 1 | 🌐 C# | 📅 2026-11-20 - Experimental port of Microsoft's React-style framework for building UI from C# components and hooks without XAML.
* [Chinook.DynamicMvvm](https://github.com/nventive/Chinook.DynamicMvvm) ⭐ 12 | 🐛 5 | 🌐 C# | 📅 2026-01-20 - Declarative and extensible ViewModels, properties and commands, by nventive.
* [Chinook.Navigation](https://github.com/nventive/Chinook.Navigation) ⭐ 11 | 🐛 3 | 🌐 C# | 📅 2026-01-19 - ViewModel-first stack, sections and modal navigation, by nventive.
* [XAML Behaviors for Uno](https://github.com/unoplatform/Uno.XamlBehaviors) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2026-11-12 - Port of XAML Behaviors with triggers, actions and InvokeCommandAction for non-Windows targets.
* [Singulink UI Toolkit](https://github.com/Singulink/Singulink.UI) ⭐ 4 | 🐛 1 | 🌐 C# | 📅 2026-11-19 - Strongly typed, deep-linkable MVVM navigation plus a task runner, XAML helpers and trimmed Fluent icon packs.
* [ReactiveUI.Uno](https://github.com/reactiveui/ReactiveUI.Uno) ⭐ 2 | 🐛 5 | 🌐 C# | 📅 2026-11-20 - ReactiveUI integration with view bases, activation, routing, bindings and schedulers.
* [MVx.Observable](https://www.nuget.org/packages/MVx.Observable/) - A (mostly) unopinionated, light-weight alternative to ReactiveUI provided as a library *not a framework*.
* [Prism](https://prismlibrary.com/) - Framework for building loosely coupled, modular, maintainable, and testable XAML applications.
* [Microsoft MVVM Toolkit](https://learn.microsoft.com/dotnet/communitytoolkit/mvvm/) - Modern, fast, and modular MVVM library.

### Dependency Injection

* [Pure.DI](https://github.com/DevTeam/Pure.DI) ⭐ 851 | 🐛 3 | 🌐 C# | 📅 2026-11-20 - Generates dependency injection object graphs at compile time without requiring a runtime container by [Nikolay Pianikov](https://github.com/NikolayPianikov).

### Integrations

* [Shiny](https://github.com/shinyorg/shiny) ⭐ 1,594 | 🐛 1 | 🌐 C# | 📅 2026-11-20 - Device and background services such as jobs, Bluetooth LE, push notifications, geofencing and GPS.
* [32feet.NET](https://github.com/inthehand/32feet) ⭐ 994 | 🐛 155 | 🌐 C# | 📅 2026-11-18 - Bluetooth Classic, Bluetooth LE and NFC library with an API modeled on Web Bluetooth.
* [Datasync Community Toolkit](https://github.com/CommunityToolkit/Datasync) ⭐ 186 | 🐛 3 | 🌐 C# | 📅 2026-11-13 - Offline-capable data synchronization between client apps and an ASP.NET Core backend.
* [Uno.SQLitePCLRaw.Wasm](https://github.com/unoplatform/Uno.SQLitePCLRaw.Wasm) ⭐ 36 | 🐛 0 | 🌐 C# | 📅 2024-10-26 - SQLitePCLRaw provider that brings SQLite, sqlite-net and EF Core to WebAssembly apps.
* [Uno.RevenueCat](https://github.com/MartinZikmund/Uno.RevenueCat) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2026-11-01 - RevenueCat in-app purchases and subscriptions for Android and iOS.
* [Uno.AdMob](https://github.com/MartinZikmund/Uno.AdMob) ⭐ 0 | 🐛 8 | 🌐 C# | 📅 2026-11-18 - Google AdMob banner, interstitial, rewarded and app open ads with UMP consent on Android and iOS.

### Compatibility

* [C# Markup 2](https://github.com/VincentH-Net/CSharpForMarkup) ⭐ 842 | 🐛 7 | 🌐 C# | 📅 2026-05-29 - Concise, declarative C# UI markup with Uno Toolkit, Navigation and MVUX support and `dotnet new` templates.
* [Elmish.Uno](https://github.com/xperiandri/Elmish.Uno) ⭐ 16 | 🐛 10 | 🌐 F# | 📅 2025-07-22 - Half-Elmish framework for apps written in F#.
* [Majorsilence.Forms](https://github.com/majorsilence/Majorsilence.Forms) ⭐ 12 | 🐛 17 | 🌐 C# | 📅 2026-11-19 - Cross-platform Windows Forms API that runs WinForms-style apps on desktop, mobile and WebAssembly.
* [SignalR](https://learn.microsoft.com/aspnet/core/signalr/introduction) - [Cross-Platform Real-Time Communication with Uno & SignalR](https://ian.bebbs.co.uk/posts/UnoChat) - Integration example for the SignalR framework.
* [C# Markup](https://platform.uno/docs/articles/external/uno.extensions/doc/Learn/Markup/Overview.html) - Fluent C# API for declaring UI, including bindings, styles and resources, as an alternative to XAML.
* [.NET MAUI Embedding](https://platform.uno/docs/articles/external/uno.extensions/doc/Learn/Maui/MauiOverview.html) - Hosts .NET MAUI controls, including third-party vendor suites, inside apps on iOS, Android, macOS and Windows.

## Samples

* [League of Legends Client](https://github.com/JamesnetGroup/leagueoflegends-uno) ⭐ 66 | 🐛 0 | 🌐 C# | 📅 2025-02-15 - Recreation of the League of Legends client UI showing custom controls and a modular architecture for large XAML apps.
* [Uno Chefs](https://github.com/unoplatform/uno.chefs) ⭐ 37 | 🐛 55 | 🌐 C# | 📅 2026-11-09 - Official recipe reference app demonstrating MVUX, navigation, Material theming and Toolkit controls.
* [nventive Uno Application Template](https://github.com/nventive/UnoApplicationTemplate) ⭐ 36 | 🐛 4 | 🌐 C# | 📅 2026-02-16 - Production-grade dotnet new mobile app template with MVVM, dependency injection, logging and built-in diagnostic tools.
* [DevTKSS Uno Sample Apps](https://github.com/DevTKSS/DevTKSS.Uno.SampleApps) ⭐ 5 | 🐛 6 | 🌐 C# | 📅 2026-03-14 - Bilingual German and English sample apps and step-by-step tutorials covering MVUX, navigation and other Uno.Extensions features.
* [Fun with SkiaSharp](https://github.com/MartinZikmund/fun-with-skiasharp) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2026-06-30 - Nineteen SkiaSharp visual demos and minigames from the SkiaSharp 4 launch event, with a live WebAssembly gallery.
* [Wayfarer](https://github.com/MartinZikmund/Wayfarer) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2026-11-09 - Travel journal sample showcasing LinedFlowLayout, RichEditBox, Composition animations, multi-window and tvOS support.
* [Uno App Template](https://github.com/MartinZikmund/uno-app-template) ⭐ 0 | 🐛 63 | 🌐 C# | 📅 2026-11-20 - Opinionated app template with MVVM, DI, navigation, localization, versioning and multi-store release pipelines.

## Live apps

* [Uno Playground](https://playground.platform.uno) - Experiment with C# and XAML right from the browser.
* [Uno Calculator](https://calculator.platform.uno/) - WebAssembly port of the Windows Calculator app.
* [NuGet.info](https://nuget.info/) - Modernized version of NuGet Package Explorer application.
* [Windows Community Toolkit Gallery](https://toolkitlabs.dev/) - Live gallery of Windows Community Toolkit controls and helpers, including experimental Labs components.
* [Unexpected APIs in Uno Platform](https://unexpectedapis.uno/) - Demo app including various UI and non-UI APIs that you can use in Uno Platform.
* [Uno Gallery](https://gallery.platform.uno/) - Browser version of the control and theme gallery with live samples and code snippets.
* [Uno Space](https://wieslawsoltes.github.io/UnoSpace/) - Seventeen local-first desktop-class apps, from a word processor and spreadsheet to PDF, CAD and Git tools, running in the browser.
* [Fluent Stopwatch](https://fluentstopwatch.uno/) - Stopwatch with multiple timers, laps and history, by Martin Zikmund.
* [XAML-MAN](https://martinzikmund.github.io/XamlMan/) - Arcade-accurate Pac-Man clone rendered entirely in XAML, by Martin Zikmund.
* [UnoDOOM](https://happy-tree-0e73b8e10.3.azurestaticapps.net/) - Playable cross-platform DOOM port based on ManagedDoom, with a bundled Freedoom WAD, by Martin Zikmund.
* [Roslyn Quoter](https://roslynquoter-wasm.platform.uno/) - Shows the Roslyn SyntaxFactory API calls that construct any given C# program.
* [SQLite + Entity Framework Core in WebAssembly](https://sqliteefcore-wasm.platform.uno/) - In-browser C# editor that compiles code with Roslyn and runs Entity Framework Core against SQLite.

## Open-source apps

* [Sefirah](https://github.com/shrimqy/Sefirah) ⭐ 3,108 | 🐛 173 | 🌐 C# | 📅 2026-11-20 - Phone Link alternative that syncs clipboard, notifications, files and media between Android and the desktop.
* [NuGet Package Explorer](https://github.com/NuGetPackageExplorer/NuGetPackageExplorer/tree/main/Uno) ⭐ 2,552 | 🐛 109 | 🌐 C# | 📅 2026-10-08 - Source code of the Uno Platform version of NuGet Package Explorer.
* [2fast](https://github.com/2fast-team/2fast) ⭐ 574 | 🐛 35 | 🌐 C# | 📅 2026-10-25 - Two-factor TOTP authenticator for Windows, Android, iOS, Linux and macOS.
* [Eppie](https://github.com/Eppie-io/Eppie-App) ⭐ 421 | 🐛 65 | 🌐 C# | 📅 2026-11-17 - Encrypted peer-to-peer email client that also works with regular IMAP/SMTP accounts.
* [Uno Calculator](https://github.com/unoplatform/calculator) ⭐ 413 | 🐛 61 | 🌐 C# | 📅 2026-10-14 - Port of the open-source Windows Calculator to C# for iOS, macOS, Android, WebAssembly and Linux.
* [SecureFolderFS](https://github.com/securefolderfs-community/SecureFolderFS) ⭐ 287 | 🐛 7 | 🌐 C# | 📅 2026-10-09 - File encryption app that protects folders as vaults with on-the-fly encryption.
* [Uno Playground](https://github.com/unoplatform/Uno.Playground) ⭐ 220 | 🐛 28 | 🌐 C# | 📅 2026-10-21 - Source code of the in-browser playground, with UI samples.
* [Strix Music](https://github.com/Arlodotexe/strix-music) ⭐ 150 | 🐛 41 | 🌐 C# | 📅 2026-05-19 - Alpha-stage music player and SDK that merges multiple music sources into a single reskinnable library.
* [Azure Key Vault Explorer](https://github.com/cricketthomas/AzureKeyVaultExplorer) ⭐ 120 | 🐛 17 | 🌐 C# | 📅 2026-11-19 - Desktop app for finding, filtering and reading secrets, keys and certificates across Azure Key Vaults.
* [asERP](https://github.com/andrich-software/asERP) ⭐ 96 | 🐛 14 | 🌐 C# | 📅 2026-11-09 - Self-hosted retail ERP toolkit with a REST API and cross-platform desktop, web and mobile clients.
* [UADO](https://github.com/unoplatform/uado) ⭐ 83 | 🐛 25 | 🌐 C# | 📅 2022-04-16 - Azure DevOps backlog viewer.
* [Emerald](https://github.com/RiversideValley/Emerald) ⭐ 83 | 🐛 10 | 🌐 C# | 📅 2026-11-16 - Minecraft launcher for Windows, macOS and Linux with multi-instance profiles.
* [Ch9](https://github.com/unoplatform/Uno.Ch9) ⭐ 72 | 🐛 21 | 🌐 C# | 📅 2023-11-08 - Channel 9 browser app.
* [Scrubbler 2](https://github.com/Scrubbler-Dev/Scrubbler-2) ⭐ 31 | 🐛 1 | 🌐 C# | 📅 2026-09-23 - Plugin-based manual scrobbler for listens that a player or service failed to submit.
* [StoryCAD](https://github.com/storybuilder-org/StoryCAD) ⭐ 30 | 🐛 36 | 🌐 C# | 📅 2026-11-20 - Free outlining tool that helps fiction writers plan characters, plots and settings.
* [TextSpace](https://github.com/wieslawsoltes/TextSpace) ⭐ 20 | 🐛 1 | 🌐 C# | 📅 2026-09-30 - Local-first word processor with paginated editing, a ribbon and DOCX/PDF export, running on desktop and in the browser.
* [Sentry Desktop Crash Reporter](https://github.com/getsentry/sentry-desktop-crash-reporter) ⭐ 16 | 🐛 7 | 🌐 C# | 📅 2026-11-20 - Sentry's cross-platform crash reporter that asks users for feedback and consent before submitting a report.
* [Celbridge](https://github.com/celbridge-org/celbridge) ⭐ 14 | 🐛 63 | 🌐 C# | 📅 2026-11-20 - Workbench for building HTML-based tools for game dev teams, with Python scripting and spreadsheet support.
* [SubZero Framework Edition](https://github.com/TekuSP/SubZeroFramework) ⭐ 13 | 🐛 7 | 🌐 C# | 📅 2026-11-19 - Fan control and thermal telemetry app for Framework laptops on Windows and Linux.
* [DotUninstall](https://github.com/lextudio/DotUninstall) ⭐ 12 | 🐛 1 | 🌐 C# | 📅 2026-11-15 - Graphical front end for the dotnet-core-uninstall tool that removes old .NET SDKs and runtimes on Windows and macOS.
* [Matroska Batch Flow](https://github.com/TimGels/Matroska-Batch-Flow) ⭐ 11 | 🐛 9 | 🌐 C# | 📅 2026-11-15 - Batch editor for Matroska (MKV) container and track properties across many files.
* [Recurrents](https://github.com/morning4coffe-dev/recurrents) ⭐ 11 | 🐛 16 | 🌐 C# | 📅 2026-08-22 - Subscription tracker with payment reminders and spending overview.
* [Pāli Practice](https://github.com/DhammaBytes/PaliPractice) ⭐ 9 | 🐛 1 | 🌐 C# | 📅 2026-09-14 - Flashcard app that uses spaced repetition to drill Pāli noun declensions and verb conjugations.
* [Elapsed](https://github.com/hackclub/elapsed) ⭐ 9 | 🐛 27 | 🌐 C# | 📅 2026-07-01 - Desktop and mobile client for Hack Club's Lapse timelapse programme, with a companion CLI.
* [PixlPunkt](https://github.com/ChadRoesler/PixlPunkt) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2026-11-10 - Pixel art editor with animation and a plugin SDK, with builds for Windows, macOS and Linux.
* [HouzLinc](https://github.com/Lakeside-Apps/HouzLinc) ⭐ 5 | 🐛 43 | 🌐 C# | 📅 2026-11-11 - Local-network configuration app for Insteon home automation devices and scenes.
* [CODuo](https://github.com/ibebbs/CODuo) ⭐ 4 | 🐛 3 | 🌐 C# | 📅 2024-07-09 - Visualizing the environmental impact of current and forecast energy generation in the UK. Designed for use on both single and dual-screen devices.
* [MZikmund.dev](https://github.com/MartinZikmund/mzikmund) ⭐ 4 | 🐛 84 | 🌐 C# | 📅 2026-11-20 - Personal website and blog platform with an ASP.NET Core backend and a cross-platform reader and admin app.
* [RoMi](https://github.com/DrHardReset/RoMi) ⭐ 4 | 🐛 12 | 🌐 C# | 📅 2026-11-18 - Calculator for the SysEx MIDI messages that remote-control Roland keyboards and synthesizers.
* [Daily Reflection](https://github.com/kazo0/DailyReflection) ⭐ 4 | 🐛 4 | 🌐 C# | 📅 2026-11-14 - Reader for the A.A. Daily Reflections, migrated in place from Xamarin.Forms and live on Google Play and the App Store.
* [Salmon Egg](https://github.com/salmonloop/salmon-egg) ⭐ 2 | 🐛 7 | 🌐 C# | 📅 2026-10-14 - Desktop client for AI agents over the Agent Client Protocol, with session history, tool-call review and terminal workflows.
* [Fluent Stopwatch](https://github.com/MartinZikmund/stopwatch) ⭐ 1 | 🐛 51 | 🌐 C# | 📅 2026-11-13 - Stopwatch with multiple timers, laps and history, also usable in the browser.
* [Daily Plants](https://github.com/MartinZikmund/daily-plants) ⭐ 0 | 🐛 43 | 🌐 C# | 📅 2026-11-20 - Private checklist for Dr. Greger's Daily Dozen and Twenty-One Tweaks, with streaks, statistics and 21 languages.
* [Uno Cockpit](https://github.com/MartinZikmund/UnoCockpit) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2026-11-15 - WebAssembly dashboard for in-car browsers with a trip HUD, gamepad arcade game, photo booth and sensor lab.

## Games

* [Astro Odyssey](https://github.com/asadullah-refat-89/astro-odyssey-uno-platform) ⭐ 25 | 🐛 0 | 🌐 C# | 📅 2026-01-06 - Browser space shooter where you destroy meteors and enemies and battle level bosses.
* [UnoDOOM](https://github.com/MartinZikmund/UnoDoom) ⭐ 7 | 🐛 2 | 🌐 C# | 📅 2026-07-09 - DOOM port built on ManagedDoom with touch, keyboard and gamepad controls, playable in the browser.
* [XAML-MAN](https://github.com/MartinZikmund/XamlMan) ⭐ 0 | 🐛 0 | 🌐 C# | 📅 2026-09-18 - Faithful Pac-Man clone with arcade-accurate ghost AI, drawn entirely with XAML shapes and playable in the browser.

## Case Studies

* [Case Studies](https://platform.uno/case-studies/) - Official success stories from companies such as Toyota, Kahua, Air Canada, TradeZero and Microsoft.
* [Toyota Migrates Mobile App to Uno Platform](https://platform.uno/blog/toyota-migrates-mobile-app-to-uno-platform/) - How Toyota moved its North American plant line-of-business apps off Xamarin.Forms.
* [Windows Community Toolkit - How Microsoft Uses Uno Platform to Ship Fast](https://platform.uno/blog/windows-community-toolkit-how-microsoft-uses-uno-platform-to-ship-fast/) - Guest post by Michael Hawker on how the Windows Community Toolkit ships WinUI 2, WinUI 3 and WebAssembly from one codebase.
* [Sentry Chooses Uno Platform](https://platform.uno/blog/sentry-chooses-uno-platform-a-success-story/) - How Sentry built its open-source desktop crash reporter for Windows, macOS and Linux.

## Blogs

* [Official Uno Platform blog](https://platform.uno/blog/) - Lists latest release notes, tutorials, and articles by Uno Platform maintainers as well as external contributors.
* [Jerome Laban's blog](https://jaylee.org/) - Blog of the CTO of Uno Platform.
* [Martin Zikmund blog](https://mzikmund.dev/blog/categories/uno-platform) - Posts on WebAssembly, device APIs, sample apps and fun projects like DOOM, by Martin Zikmund.
* [Nick's .NET Travels](https://nicksnettravels.builttoroam.com/tag/uno/) - Uno Platform blog posts by Nick Randolph.
* [IObservable\<Opinion>](https://ian.bebbs.co.uk/tags/uno-platform) - Uno Platform blog posts by Ian Bebbington.
* [InfoQ Uno Platform News](https://www.infoq.com/uno-platform/) - Independent release-by-release news coverage, mostly by Almir Vuk and Edin Kapić.
* [Steve Bilogan's Blog](https://kazo0.dev/) - Toolkit Tuesdays, Uno Tidbits and AI agent posts by Uno Toolkit maintainer Steve Bilogan.
* [lindexi's Blog (ZH)](https://www.cnblogs.com/lindexi/tag/UNO/) - Chinese posts on WPF migration, Linux desktop quirks (UOS, Kylin, X11) and framework internals by lindexi.

## Articles

* [WPF and Legacy App Migration Guides](https://platform.uno/blog/article_tags/migration/) - Official article series on migrating WPF and Xamarin.Forms apps, covering scoping, XAML mapping, triggers, resources, testing and incremental adoption.
* [How Uno Platform Uses .NET, MCP, and AI to Build High Quality Apps](https://devblogs.microsoft.com/dotnet/how-uno-platform-uses-dotnet-mcp-ai-to-build-high-quality-apps/) - Tour of the docs and app MCP servers, agent skills and Studio, by Sam Basu on the .NET Blog.

## Courses and Tutorials

* [Counter App Tutorial](https://platform.uno/docs/articles/getting-started/counterapp/get-started-counter.html) - Step-by-step first app in XAML or C# Markup with MVVM or MVUX, plus a Hot Design variant.
* [SimpleCalc Workshop](https://platform.uno/docs/articles/external/workshops/simple-calc/README.html) - Hands-on workshop building a calculator with XAML or C# Markup, MVVM or MVUX and runtime theme switching.
* [TubePlayer Workshop](https://platform.uno/docs/articles/external/workshops/tube-player/README.html) - Multi-module workshop building a YouTube search and playback app with C# Markup, MVUX, navigation and optional Figma import.
* [Uno Platform From Start to Finish](https://www.devforge.com/courses/uno-from-start-to-finish/) - Paid 66-lesson video course covering setup, MVUX, Uno Toolkit, Hot Design, Figma to code and MCPs. By Tim Corey.

## Live coding

* [Jerome Laban's Twitch](https://www.twitch.tv/jeromelaban) - Weekly Uno Platform live coding sessions (Tuesdays).
* [Martin Zikmund's Twitch](https://www.twitch.tv/martinzikmund) - Mostly Uno Platform-themed live coding sessions.
* [Martin Zikmund's Live Coding Archive](https://www.youtube.com/playlist?list=PLC0wF4Qw6SDNu61eMpdGCw-c5RR2Tk2R6) - Recorded streams porting WinUI APIs into the framework, plus walkthroughs on contributing to it.
* [Uno Platform Live Coding Archive](https://www.youtube.com/playlist?list=PLl_OlDcUya9pRqt9A0vpyi89Vl-uq3nSb) - Recordings of CTO Jérôme Laban's weekly streams debugging and building the framework.

## Talks

* [Introduction to open source Uno Platform](https://youtu.be/vRzTr8XYau0) - Introductory talk by Jérôme Laban about Uno Platform and what it offers.
* [Uno Platform - Your Apps Everywhere](https://youtu.be/dX69x-D6COI) - Overview of the Uno Platform ecosystem by Martin Zikmund at NDC Porto 2022.
* [Building Multi-Platform Applications with the Uno Platform](https://youtu.be/0zvzfCGO0gI) - Introduction to creating apps for multiple platforms and form factors, all while reusing your existing XAML and C# skills by Nick Randolph.
* [Разработка кросс-платформенных приложений с Uno Platform и Elmish-подходом на F# (RU)](https://www.youtube.com/watch?v=ApNGATu9RSo) - Introduction to Uno, Blend and Elmish.
* [Uno Platform - Your Apps Everywhere (NDC London 2023)](https://www.youtube.com/watch?v=BTgp9VyZSs8) - Overview of the ecosystem by Martin Zikmund at NDC London 2023.
* [How We Build an Open-Source Cross-Platform Framework in .NET](https://www.youtube.com/watch?v=ns9EiKLlxsQ) - Engineering behind the framework, from source generators and the custom MSBuild SDK to CI and C++ porting, by Martin Zikmund at Monkey Conf 2024.
* [UnoConf](https://www.youtube.com/playlist?list=PLl_OlDcUya9rp-ZbLkFHWtp2-9V-xGYFu) - Recordings from the 2019 to 2021 developer conferences, including Miguel de Icaza's keynote and sessions on Extensions, styling, testing and WPF migration.
* [Announcing Uno Platform Studio and Hot Design](https://www.youtube.com/watch?v=sJPyieyt1Rc) - Launch of Studio and the Hot Design runtime visual designer, by Jérôme Laban and Nick Randolph at .NET Conf 2024.
* [Uno Platform. Now with AI](https://www.youtube.com/watch?v=g4A_3ZCwwWg) - Generating full-stack apps with AI on top of Hot Design, by Jérôme Laban at .NET Conf 2025.
* [Best Practices for Cross-Platform .NET 8 Applications](https://www.youtube.com/watch?v=yVYhZsu7gso) - Bootstrapping a well-architected app with Extensions for navigation and localization and the MVUX reactive pattern, at .NET Conf 2023.
* [Build Modern .NET Apps with Uno Platform, AI, and Visual Tools](https://www.youtube.com/watch?v=t_cKjNtB2aU) - Hot Design, AI agents grounded by the docs and app MCP servers, and SkiaSharp rendering, by Sam Basu at Microsoft Build 2026.
* [Write Uno Time, Run Everywhere with the Uno Platform](https://www.youtube.com/watch?v=vyR38vxo4ug) - Getting started from machine setup to a contacts app backed by an existing REST API, by Joseph Guadagno at NDC London 2025.
* [Let's Build a .NET YouTube Player! For Which Platform? All of Them!](https://www.youtube.com/watch?v=Vfzdr0TRYCs) - Building a YouTube player from its original Figma designs with Toolkit and Material, by Steve Bilogan at Copenhagen Developers Festival 2024.
* [Figma Meets .NET Developers](https://www.youtube.com/watch?v=lxo5TTK1Bfw) - Smoothing the designer-developer handoff by exporting Figma designs straight into the app, by Nick Randolph at NDC Sydney 2024.
* [.NET Apps Everywhere](https://www.youtube.com/watch?v=inD_3SD0G80) - Under-the-hood tour of how a single codebase renders on every platform, by Steve Bilogan at JetBrains .NET Days Online 2025.
* [Build Beautiful .NET Apps Faster with Uno Platform](https://www.youtube.com/watch?v=u8Fkb7pjqwQ) - Building cross-platform apps in C# with full UI control, device APIs, Hot Reload and Figma integration, by Martin Zikmund at the BASTA! conference.
* [Design, Build and Publish Cross-Platform .NET Applications with Uno Platform](https://www.youtube.com/watch?v=gUubBX9xhdA) - Workshop from project creation to publishing, covering the Figma plugin, Hot Reload and Hot Design, by Nick Randolph at Indy .NET Consortium 2025.
* [Migrating WPF Apps to Web](https://www.youtube.com/watch?v=doomI2bEBno) - Architecture and implementation considerations for moving WPF apps to the web, by Daren May at UnoConf 2021.
* [Martin Zikmund's Talks](https://www.youtube.com/playlist?list=PLC0wF4Qw6SDMCHrbo9PlNC4OrJ_rV5i1U) - Recordings of Martin Zikmund's Uno talks at NDC, Visual Studio Toolbox, .NET Oxford and other events.
* [Building Linux Desktop Apps with .NET and Uno Platform](https://www.youtube.com/watch?v=OxyJYF2HgBM) - James Montemagno and Jérôme Laban build, debug and deploy Linux desktop apps from VS Code on Ubuntu.
* [Uno Platform - Now With AI! (Visual Studio Toolbox)](https://www.youtube.com/watch?v=xGJ0U_E9LC8) - Sam Basu and Jérôme Laban demo MCP-driven development, Hot Design and the Hot Design agent on Visual Studio Toolbox.

## Videos

* [Uno Platform's YouTube](https://www.youtube.com/@unoplatform) - Official YouTube channel of Uno Platform, includes new release highlights, live sessions, and tutorials.
* [Uno Tech Bites](https://www.youtube.com/playlist?list=PLl_OlDcUya9rP_fDcFrHWV3DuP7KhQKRA) - Uno Platform development learnings in bite-sized lessons.
* [Martin Zikmund's YouTube](https://www.youtube.com/@mzikmund) - Various Uno Platform-related videos and tutorials.
* [Definitive Guide to Uno Platform Contributions](https://www.youtube.com/watch?v=GIboa7CZXaw) - Two-hour walkthrough of setting up, building, debugging and contributing to the framework repository by Martin Zikmund.
* [Get Started with AI-Assisted Development](https://www.youtube.com/playlist?list=PLl_OlDcUya9rizyD8smQFO45G1Q-meutb) - Official series on agent-driven development with Claude Code, Copilot CLI, Codex, Cursor, Antigravity, MCPs and Studio.
* [Intro to Uno Platform - Full Cross-Platform C# Development](https://www.youtube.com/watch?v=Cm2FRfiAzSU) - In-depth introduction to building and deploying a single-project cross-platform app, by Tim Corey.
* [Uno Platform Webinars](https://www.youtube.com/playlist?list=PLl_OlDcUya9qeKZEF3HCFdqXuys0-RwIp) - Release webinars, product launch streams and AMA sessions from the core team.
* [VectoArt's Uno Platform Tutorials](https://www.youtube.com/playlist?list=PLqT49gV-eqe6t-sdQpW0BaJIpo8Zxuiwz) - Community tutorials on Figma-to-XAML apps, animations and the Hot Design agent, by VectoArt.

## Podcasts

* [The Modern .NET Show: One UI to Rule Them All](https://dotnetcore.show/season-6/s06e18-uno-platform-one-ui-to-rule-them-all-with-martin-zikmund/) - Martin Zikmund on WinUI everywhere, Linux support and designer-developer tooling, with Jamie Taylor in 2024.
* [.NET Rocks! 1984: Uno and .NET 10 with Sam Basu and Jérôme Laban](https://www.dotnetrocks.com/details/1984) - Jérôme Laban and Sam Basu on .NET 10, the MAUI collaboration, WebAssembly and MCP-based AI tooling.
* [.NET Rocks! 1938: Uno Hot Design with Francois Tanguay and Sasha Krsmanovic](https://www.dotnetrocks.com/details/1938) - Co-founders Francois Tanguay and Sasha Krsmanovic on Hot Design and how the framework has evolved.
* [.NET Rocks! 1882: Uno Platform Update with Nick Randolph](https://www.dotnetrocks.com/details/1882) - Nick Randolph on the Figma plugin, design-to-code workflow and CI integration.
* [.NET Rocks! 1552: Open Sourcing Uno with Francois Tanguay and Jérôme Laban](https://www.dotnetrocks.com/details/1552) - Francois Tanguay and Jérôme Laban on open-sourcing the UWP-based framework in 2018.
* [Hanselminutes 820: Multi-Platform Apps with Uno Platform's Jérôme Laban](https://hanselminutes.com/820/multi-platform-apps-with-uno-platforms-jrme-laban) - Jérôme Laban on the importance and flexibility of write-once-run-everywhere, with Scott Hanselman.
* [Software Engineering Radio 508: Jérôme Laban on Cross-Platform UI](https://se-radio.net/2022/04/episode-508-jerome-laban-on-cross-platform-ui/) - Jérôme Laban on native fidelity versus consistent design, rendering approaches and platform differences in cross-platform UI.
* [The Unhandled Exception Podcast 74: The Uno Platform and Hot Design with Jérôme Laban](https://unhandledexceptionpodcast.com/posts/0074-unoplatformandhotdesign/) - Jérôme Laban on the framework and its Hot Design visual designer, with Dan Clarke.
* [Betatalks the Podcast 92: The Uno Platform: Unlocking Cross-Platform Potential with Martin Zikmund](https://www.buzzsprout.com/1622272/episodes/15826598-92-the-uno-platform-unlocking-cross-platform-potential-with-martin-zikmund) - Martin Zikmund on cross-platform development, contributing to the framework and how it compares with alternatives.
* [Blue Blazes S04E01: Uno Platform featuring Sam Basu](https://www.youtube.com/watch?v=rqm_54Y8h8U) - Sam Basu on native and Skia rendering paths and how the framework compares with MAUI, React Native and Flutter, with Jonathan Tower.

## Books

* [Getting Started with the Uno Platform and WinUI 3 (2022/09)](https://link.springer.com/book/10.1007/978-1-4842-8248-9) - Hands-on building of cross-platform desktop, mobile, and web applications that can run anywhere. By Skye Hoefling.
* [Creating Cross-Platform C# Applications with Uno Platform (2021/08)](https://www.packtpub.com/en-us/product/creating-cross-platform-c-applications-with-uno-platform-9781801078498) - Build apps with C# and XAML that run on Windows, macOS, iOS, Android, and WebAssembly. By Matt Lacey and Marcel Alexander Wagner.
* [Uno Platform Succinctly](https://www.syncfusion.com/succinctly-free-ebooks/uno-platform-succinctly) - Free introductory ebook by Ed Freitas, published by Syncfusion.

## Contributing

Your contributions are welcome! Please read the [contribution guidelines](contributing.md) before creating a pull request.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-20._
