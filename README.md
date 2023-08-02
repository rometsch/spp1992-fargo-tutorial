# spp1992-fargo-tutorial

A tutorial on FargoCPT at the SPP1992 summer school.

## Add fargo to you PATH

To be able to call fargo from anywhere, you need to add it to your PATH. To do so, open your `.bashrc` or `.zshrc` file and add the following line:

```bash
export PATH="$PATH:/path/to/fargo_repository"
```

## Parameter definitions

The documentation is not finished, but there is the `parameter_descriptions.txt` file. 
It contains a description of all the parameters. Use the search function of your editor.

Here is a list of parameters you might want to ues in this session:

- DiskFeedback: turn on migration
- HydroFrameCenter: select the center of the hydro grid
- IntegrateParticles: add particles, search for the other parameters with particles
- IndirectTermMode: try to break the simulation in a binary setup with HydroFrameCenter=Secondary
- Alphaviscosity: value of the alpha viscosity