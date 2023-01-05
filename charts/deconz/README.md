# DeCONZ Helm Chart
## General information
*This chart is unofficial and in no way affiliated with the developers of the DeCONZ software.*

**Work-in-progress! If it breaks, everyone can keep their own pieces**

I'm providing this image in hopes it will be useful to others, but changes are driven by my own needs. Feel free to file an issue or pull request though - the more people can benefit from this, the better.
## Notes
This chart will serve DeConz app on port 80. If you wish to use certificates, configure Ingress for that. The `values.yaml` directives *should* work.
Other connections, like websocket and different VNC systems, work through NodePorts. Check your cluster for correct values.
The environment variables used for configuring the app can be set in the `values.yaml` file.