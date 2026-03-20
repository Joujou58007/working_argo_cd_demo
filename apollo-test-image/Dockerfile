# FROM arm64v8/busybox:latest

# # This is now guaranteed to be ARM64 only
# CMD ["sh", "-c", "echo '=== APOLLO TEST IMAGE ===' && echo 'To infinity and beyond!' && echo 'Pulled through your K3s proxy cache on ARM64!' && sleep infinity"]
FROM busybox:1.36

# This image will print the message once and then sleep forever
# (exactly like your DaemonSet, but now it's baked into the image)
CMD ["sh", "-c", "echo '=== APOLLO TEST IMAGE ===' && echo 'To infinity and beyond!' && echo 'Pulled through your K3s proxy cache!' && sleep infinity"]
CMD ["sh", "-c", "./LatencyJitterPthreads"]