# Julia Ocean Sciences Meeting 2020 workshop

Practical information :

https://agu.confex.com/agu/osm20/meetingapp.cgi/Session/92105

- workshop title: Julia (language) users and tools for oceanography
- time: Tuesday, 18 February 2020 @ 12:45 - 13:45
- location: Marriott Marquis - Point Loma, L1

## Workshop description

_below is the original workshop proposal_

There has been a visible uptick in oceanography and climate applications of the Julia language since it reached the v1.0 milestone last year. The growth and appeal for this language were recently highlighted by Nature magazine. It seems very timely to offer this rapidly growing community of open source developers and users an opportunity to meet in person, advertise their recent efforts, and engage with the oceanographic community at large. A tentative agenda for this workshop would include: a brief general presentation of Julia, a survey of existing efforts, a hackathon-type session with both experienced and new users interacting, and open-ended discussion time.

## Workshop outline

_below is the current, still evolving, workshop outline_

### intro (G.F. 15')

- workshop outline and motivation
- why should you want to use Julia?
- how can you get started with Julia?
	- [julialan.org](https://julialang.org)
- what are Julia's salient features?
- state of the ocean & climate stack?

### state of the Julia ocean stack (10 x 2' contributions)


As for almost all open source efforts, listed packages should be regarded as collaborative & ongoing development projects. They are under version control, documented as much as possible, and can generally be installed via `Julia`'s awesome [package manager](https://julialang.github.io/Pkg.jl/v1/).

_The list is a work in progress. Also categories 1. 2. and 3. below are approximate -- some packages arguably belong in 1. 2. and 3._

1. plotting, I/O, and data analysis packages
	- [Plots.jl](http://docs.juliaplots.org/latest/), [PyPlot.jl](https://github.com/JuliaPy/PyPlot.jl), [Makie.jl](http://makie.juliaplots.org/stable), ... (volunteer ?)
	- [NetCDF.jl](https://juliageo.org/NetCDF.jl/dev/), [NCTiles.jl](https://github.com/gaelforget/NCTiles.jl), [Zarr.jl](https://meggart.github.io/Zarr.jl/latest/), [CSV.jl](https://juliadata.github.io/CSV.jl/stable/), ... (volunteer ?)
	- [DataFrames.jl](http://juliadata.github.io/DataFrames.jl/stable/), [ClimateTools.jl](https://juliaclimate.github.io/ClimateTools.jl/stable/), [ESDL.jl](https://github.com/esa-esdl/ESDL.jl), ... (volunteer ?)

2. common ocean models, analysis tools, and data sets
	- [GlobalOceanNotebooks](https://github.com/JuliaClimate/GlobalOceanNotebooks), [MeshArrays.jl](https://juliaclimate.github.io/MeshArrays.jl/dev/), [IndividualDisplacements.jl](https://juliaclimate.github.io/IndividualDisplacements.jl/dev/), [ArgoData.jl](https://gaelforget.github.io/ArgoData.jl/dev/), [ClimateTasks.jl](https://gaelforget.github.io/ClimateTasks.jl/dev/), ... (@gaelforget)
	- [AIBECS.jl](https://briochemc.github.io/AIBECS.jl/stable/), [WorldOceanAtlasTools.jl](https://github.com/briochemc/WorldOceanAtlasTools.jl), [OceanographyCruises.jl](https://github.com/briochemc/OceanographyCruises.jl), ... (@briochemc)
	- [NCDatasets.jl](https://alexander-barth.github.io/NCDatasets.jl/dev/), [DIVAnd.jl](https://gher-ulg.github.io/DIVAnd.jl/latest/), [PhysOcean.jl](https://github.com/gher-ulg/PhysOcean.jl) (@Alexander-Barth, to be confirmed)

3. models written in Julia

	- [ShallowWaters.jl](https://github.com/milankl/ShallowWaters.jl) (@milankl)
	- [Oceananigans.jl](https://github.com/climate-machine/Oceananigans.jl) (@ali-ramadan or @glwagner)
	- [geophysicalflows.jl](https://github.com/FourierFlows/GeophysicalFlows.jl) (@navidcy or @glwagner)

_New to github etc? See e.g. [these guides](https://guides.github.com) and `Lecture03` in [these tutorials](https://github.com/PraCTES/MIT-PraCTES); it's all user-friendly._

### Q & A (20')

Please feel free to add questions ahead of, during, and after the workshop in [this thread](https://github.com/gaelforget/JuliaOceanSciencesMeeting2020/issues/4) for example.

### looking forward (G.F. 5')

- this repo; during & after OSM020
- github organizations & contributors
- JuliaClimate and JuliaOcean organizations
