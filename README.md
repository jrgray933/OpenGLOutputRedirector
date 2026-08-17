# OpenGLOutputRedirector
Intercepts an OpenGL process in order to tie it to a GPU that your primary display is not plugged into. This allows you to use a high-performance GPU for rendering the game, rather than it defaulting to the GPU your display is plugged into. This is ideal for multi-GPU configurations such as Lossless Scaling.

Use:
Drag the app window onto the display you would like the game to be played on. It will detect this as the output display, with another display chosen for the render GPU. Target a game process and click launch.

Games that use a launcher can be targeted by using "This executable launches a child game process." Target the launcher, then add the final game executable process name in the secondary field. This is a wildcard match.
