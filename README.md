# platform-config-demo

Currently only filled out the develop release stream.

You can render the environment variables of any part of the tree using `render.sh`

render.sh expects the following options:

```
-r, --release_stream     Set the release stream to use when rendering the output (required)
-t, --team      Set the team expected to be used for the service (required)
-s, --service      Sets the name of the service to render (required)
-c, --client      Chooses the client to render overrides for, if applicable (optional)
```
