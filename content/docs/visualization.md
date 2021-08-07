---
title: "Visualization"
weight: 240
---

# Visualization in Julia

> Plotting libraries for statistical Charts, Graphs, Plots, Histograms, Maps.

## Plotting

**Resources**

- [Org: Julia Plots](https://github.com/JuliaPlots)
- [PlotsGallery.jl](https://github.com/goropikari/PlotsGallery.jl) : An unofficial `Plots.jl` Gallery inspired by MATLAB Plot Gallery.
- [Various Julia plotting examples using PyPlot](https://gist.github.com/gizmaa/7214002)
- Drawing [2.7 billion points (22gb) in 10 seconds](https://medium.com/@sdanisch/drawing-2-7-billion-points-in-10s-ecc8c85ca8fa) on a normal desktop computer.

**Packages**

- [ASCIIPlots.jl](https://github.com/johnmyleswhite/ASCIIPlots.jl) : Generate simple plots as ASCII art in Julia.
- [BlenderPlot.jl](https://github.com/wookay/BlenderPlot.jl) : a prototype version of the bar_chart plot on Blender using PyCall.
- [CMDimCircuits.jl](https://github.com/ma-laforge/CMDimCircuits.jl) : Parametric analysis/visualization of model/measurement/simulation results. The sister package for continuous function interpolation: [CMDimData.jl](https://github.com/ma-laforge/CMDimData.jl).
- [CMPlot.jl](https://github.com/g-insana/CMPlot.jl) : Cloudy Mountain Plot inspired by Violin, Bean and Pirate Plots.
- [CrossfilterCharts.jl](https://github.com/tawheeler/CrossfilterCharts.jl) : A Julia package for automagical DC.js linked charts in your IJulia notebook.
- [DataVoyager.jl](https://github.com/davidanthoff/DataVoyager.jl) : Julia wrapper for the Voyager data exploration tool.
- [Displaz.jl](https://github.com/c42f/Displaz.jl) : Julia bindings for [lidar viewer displaz](http://c42f.github.io/displaz).
- [ECharts.jl](https://github.com/randyzwitch/ECharts.jl): Julia package for the Apache ECharts v4 visualization library.
- [Gadfly.jl](https://github.com/GiovineItalia/Gadfly.jl) : A statistical graphics plotting and data visualization system. [Gadfly Reference Cards](https://github.com/john9631/JuliaDocs) and rendering to an [SVG file using the D3 browser interface](https://github.com/dcjones/Gadfly.jl#using-the-d3-backend).
- [Gaston.jl](https://github.com/mbaz/Gaston.jl) : A julia front-end for [gnuplot](http://gnuplot.info/).
- [GMT.jl](https://github.com/joa-quim/GMT.jl) : is a package containing Julia bindings for the [Generic Mapping Tools](https://github.com/GenericMappingTools/gmt) Library.
- [GR.jl](https://github.com/jheinen/GR.jl) : This module provides a Julia interface to the [GR framework](http://gr-framework.org/) graphics library.
- [GracePlot.jl](https://github.com/ma-laforge/GracePlot.jl) : Publication-quality plotting for julia using Grace/xmgrace.
- [GraphMakie.jl](https://github.com/JuliaPlots/GraphMakie.jl) : Plotting graphs with [Makie.jl][].
- [GraphPlot.jl](https://github.com/afternone/GraphPlot.jl) : Graph visualization for Julia.
- [Immerse.jl](https://github.com/JuliaGraphics/Immerse.jl) : Dive deeper into your data with interactive graphics.
- [ImPlot.jl](https://github.com/wsphillips/ImPlot.jl) : an interface to [cimplot](https://github.com/cimgui/cimplot), which is an auto-generated C API to [implot](https://github.com/epezent/implot), a C++ plotting extension library for [imgui](https://github.com/ocornut/imgui).
- [Javis.jl](https://github.com/Wikunia/Javis.jl): Julia Animations and Visualizations. [JuliaCon 2021 Video](https://youtu.be/ckvsc6ukdOc).
- [Makie.jl][] : High level plotting on the GPU.
- [PGFPlots.jl](https://github.com/JuliaTeX/PGFPlots.jl) : Plotting tool that uses the LaTeX pgfplots package (built on top of TikZ) to produce plots.
- [PGFPlotsX.jl](https://github.com/KristofferC/PGFPlotsX.jl) : Generate publication quality figures using the LaTeX library PGFPlots. It tries to have a very close mapping to the PGFPlots API as well as minimize the number of dependencies.
- [Plotly.jl](https://github.com/plotly/Plotly.jl) : A Julia wrapper for the plot.ly REST API *cloud service*.
- [PlotlyJS.jl](https://github.com/JuliaPlots/PlotlyJS.jl) : Julia library for plotting with `plotly.js`.
- [Plots.jl][] : An API/interface and wrapper that sits above other plotting packages (backends) and gives the user simple, consistent, and flexible plotting commands.
- [PyPlot.jl](https://github.com/JuliaPy/PyPlot.jl) : Plotting for Julia based on `matplotlib.pyplot`.
- [RoMEPlotting.jl](https://github.com/JuliaRobotics/RoMEPlotting.jl): 2D plotting functionality for the RoME.jl package. It's part of the [Caesar.jl](http://www.github.com/JuliaRobotics/Caesar.jl) package.
- [SandDance.jl](https://github.com/queryverse/SandDance.jl) : Julia bindings for [MS Sanddance](https://microsoft.github.io/SandDance/)
- [SimplePlots.jl](https://github.com/djsegal/SimplePlots.jl) : Plots in 5 seconds or your money back.
- [StatsPlots.jl](https://github.com/JuliaPlots/StatsPlots.jl) : Statistical plotting recipes for [Plots.jl][].
- [UnicodePlots.jl](https://github.com/Evizero/UnicodePlots.jl) : Unicode plotting for the REPL in Julia.
- [VegaLite.jl](https://github.com/queryverse/VegaLite.jl) : This package provides access to the Vega-Lite high-level [visualization grammar](http://vega.github.io/vega-lite/) in Julia.
- [VennEuler.jl](https://github.com/HarlanH/VennEuler.jl) : Generate area-proportional Venn/Euler diagrams in Julia.
- [Winston.jl](https://github.com/JuliaGraphics/Winston.jl) : 2D plotting for Julia.


## Infrastructure packages

- [Cairo.jl](https://github.com/JuliaGraphics/Cairo.jl) : Bindings for the Cairo graphics library.
- [Colors.jl](https://github.com/JuliaGraphics/Colors.jl) : Color manipulation utilities for Julia.
- [ColorTypes.jl](https://github.com/JuliaGraphics/ColorTypes.jl) : Color primitives for Julia, based on FixedSizeArrays.
- [ColorVectorSpace.jl](https://github.com/JuliaGraphics/ColorVectorSpace.jl) : This package is an add-on to ColorTypes, and provides fast mathematical operations for objects with types such as RGB and Gray - Treat colors as if they are n-vectors for the purposes of arithmetic.
- [GLFW.jl](https://github.com/JuliaGL/GLFW.jl) : Julia interface to [GLFW](http://www.glfw.org/), a multi-platform library for creating windows with OpenGL contexts and managing input and events.
- [GraphRecipes.jl](https://github.com/JuliaPlots/GraphRecipes.jl) : Graph-related recipes to be used with [Plots.jl][].
- [ImplicitEquations.jl](https://github.com/jverzani/ImplicitEquations.jl) : Plotting implicit equations and inequalities.
- [PlotlyBase.jl](https://github.com/sglyon/PlotlyBase.jl) : Generate plotly.js JSON in Julia.
- [PlotRecipes.jl](https://github.com/JuliaPlots/PlotRecipes.jl) : Assorted recipes to be used with [Plots.jl][].
- [PlotThemes.jl](https://github.com/JuliaPlots/PlotThemes.jl) : Themes for the Julia plotting package [Plots.jl][].
- [PlotUtils.jl](https://github.com/JuliaPlots/PlotUtils.jl) : Generic helper algorithms for building plotting components.
- [RecipesBase.jl](https://github.com/JuliaPlots/RecipesBase.jl) : Base package for defining transformation recipes on user types for [Plots.jl][].


[Makie.jl]: https://github.com/JuliaPlots/Makie.jl
[Plots.jl]: https://github.com/JuliaPlots/Plots.jl

---

## other packages

<details>

<summary>🏚️ Might not work in the current version of Julia</summary>

- 🏚️ [AnimatedPlots.jl](https://github.com/zyedidia/AnimatedPlots.jl) : Fast animated (and static) plots for Julia.
- 🏚️ [BBVis.jl](https://github.com/joehuchette/BBVis.jl) : Visualizations for branch-and-bound algorithms.
- 🏚️ [Bokeh.jl](https://github.com/bokeh/Bokeh.jl) : Bokeh bindings for Julia.
- 🏚️ [CData.jl](https://github.com/ma-laforge/CData.jl) : C-Data Analysis/Visualization Suite.
- 🏚️ [ComposeVideo.jl](https://github.com/arnim/ComposeVideo.jl) : Video generator for Gadfly.jl.
- 🏚️ [ECharts.jl](https://github.com/wlbksy/ECharts.jl) by @wlbksy : Julia package for [ECharts](https://github.com/ecomfe/echarts)
- 🏚️ [FalseColor.jl](https://github.com/ojwoodford/FalseColor.jl) : A Julia package to turn gridded data into pretty images.
- 🏚️ [GainPatterns.jl](https://github.com/dressel/GainPatterns.jl) : This package allows manipulation of gain patterns.
- 🏚️ [GainPatternsTex.jl](https://github.com/dressel/GainPatternsTex.jl) : Plotting gain patterns.
- 🏚️ [GLAbstraction.jl](https://github.com/JuliaGL/GLAbstraction.jl) : Abstraction library for OpenGL.
- 🏚️ [GLPlot.jl](https://github.com/SimonDanisch/GLPlot.jl) : Plotting for Julia with OpenGL.
- 🏚️ [GLVisualize.jl](https://github.com/JuliaGL/GLVisualize.jl) : Visualization library written in Julia and OpenGL.
- 🏚️ [GLWindow.jl](https://github.com/JuliaGL/GLWindow.jl) : Simple package to create an OpenGL window with an OpenGL context.
- 🏚️ [GoogleCharts.jl](https://github.com/jverzani/GoogleCharts.jl) : The Julia interface to Google Chart Tools.
- 🏚️ [GraphCentrality.jl](https://github.com/sbromberger/GraphCentrality.jl) : All centrality measures relating to graphs for degree (with indegree and outdegree), betweenness, and closeness centrality measures.
- 🏚️ [HEALPix.jl](https://github.com/mweastwood/HEALPix.jl) : Julia wrapper for [HEALPix](http://healpix.jpl.nasa.gov/).
- 🏚️ [Hinton.jl](https://github.com/ninjin/Hinton.jl) : A small Julia library for generating Hinton diagrams.
- 🏚️ [Histograms.jl](https://github.com/jpata/Histograms.jl) : Methods for handling histograms in Julia.
- 🏚️ [ImageTerm.jl](https://github.com/meggart/ImageTerm.jl) : Julia functions to plot colorful maps in the terminal.
- 🏚️ [julia-glplot](https://github.com/o-jasper/julia-glplot) : Opengl plotting - Plotting of arrays, functions, Histograms, oscilloscope style real-time plotter.
- 🏚️ [Lumira.jl](https://github.com/sbcd90/Lumira.jl) : A Julia Library which helps in the creation of SAP-Lumira extensions using Gadfly.
- 🏚️ [MinMaxFilter.jl](https://github.com/codles/MinMaxFilter.jl) : Lemire min max filter.
- 🏚️ [paper](https://github.com/andrewcooke/paper) : Crumpled paper - PDF plot in Julia.
- 🏚️ [PLplot.jl](https://github.com/wildart/PLplot.jl) : A cross-platform software package for creating scientific plots.
- 🏚️ [Qwt.jl](https://github.com/tbreloff/Qwt.jl) : 2D plotting, drawing, and GUIs using Qwt and Qt.  {Usable: 4, Robust: 3, Active: 1}
- 🏚️ [RasterIO.jl](https://github.com/wkearn/RasterIO.jl) : Simple Raster Formats for Julia.
- 🏚️ [Sparklines.jl](https://github.com/mbauman/Sparklines.jl) : A Julia implementation of spark: simple printing of unicode trendlines.
- 🏚️ [TextPlots.jl](https://github.com/sunetos/TextPlots.jl) : Fancy terminal plotting for Julia using Braille characters.
- 🏚️ [Vega.jl](https://github.com/johnmyleswhite/Vega.jl) : A Julia package for generating visualizations in Vega.
- 🏚️ [VennDiagrams.jl](https://github.com/binarybana/VennDiagrams.jl) : Generate Venn diagrams in Julia using Compose.jl.
- 🏚️ [VGPlot.jl](https://github.com/johnmyleswhite/VGPlot.jl) : A knock-off of ggplot2 in Julia using Vega.
- 🏚️ [Visualizer.jl](https://github.com/grero/Visualizer.jl) : A simple GUI for quickly panning through a collection of data.
- 🏚️ [VTK.jl](https://github.com/timholy/VTK.jl) : VTK bindings for the Julia language.
- 🏚️ [Wavelets.jl](https://github.com/tomaskrehlik/Wavelets.jl), by tomaskrehlik : Implementation of Wavelet methods in Julia.
- 🏚️ [YT.jl](https://github.com/jzuhone/YT.jl) : A Julia interface to the Python-based yt analysis toolkit. YT exposes a number of functionalities from yt.

</details>
