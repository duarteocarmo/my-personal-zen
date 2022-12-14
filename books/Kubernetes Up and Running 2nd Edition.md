# Kubernetes Up and Running 2nd Edition
- This Dockerfile produces a container image containing a static executable, but it also contains all of the Go development tools and the tools to build the React.js frontend and the source code for the application, neither of which are needed by the final application. The image, across all layers, adds up to over 500 MB. To see how we would do this with multistage builds, examine this multistage Dockerfile:
- This Dockerfile produces two images. The first is the build image, which contains the Go compiler, React.js toolchain, and source code for the program. The second is the deployment image, which simply contains the compiled binary. Building a container image using multistage builds can reduce your final container image size by hundreds of megabytes and thus dramatically speed up your deployment times, since generally, deployment latency is gated on network performance. The final image produced from this Dockerfile is somewhere around 20 MB.