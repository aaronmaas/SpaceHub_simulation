# SpaceHub_simulation
Hot Jupiter Formation in dense star cluster

This is only one simulation example of the N-body code SpaceHub to perfrom planet system scattering, https://github.com/YihanWangAstro/SpaceHub. The simulation was shown in the presentation MvSem Dynamics of the paper "Hot Jupiter Formation in dense star clusters", https://arxiv.org/abs/2011.01236.  

Params used: 
- angles isotherm
- inclination of Jupiter/Saturn random but same
- mass host star 1 solar mass, inner planet mass Jupiter, outer planet mass Saturn, interloper mass one solar mass
- inital distance jupiter 5AU, inital distance Saturn 10 AU
- impact parameter at critical closest approach b_max = 20 AU
- start distance r = 350 AU (between interloper and planet system)
- $v_\infty = 3.6 km/s $

The repositry contains only the data simulated fot the above mentioned simulation and a jupyter notebook with simple visualization code. Visualization is done by ipyvolume, you will need to install the package via pip. (There have been problems with ipyvolume and several browser for animations, I used Mozilla Firefox 89.0 without any trouble.  

