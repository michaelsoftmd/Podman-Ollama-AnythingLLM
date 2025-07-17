Your Own Private AI Pet on Linux Mint
This project is a comprehensive walkthrough for setting up a powerful and self-contained AI environment using Linux Mint. I like to think of it as giving your own "AI Pet" a home on your computer.





What I've designed is a system that uses Podman to run both Ollama and AnythingLLM in separate, rootless containers. Here’s the core philosophy behind the design:



Advanced Privacy: Everything runs on your local machine and is accessed via localhost. Your data and conversations are preserved in volumes on your drive, giving you control over them.




Rootless and Secure: The entire setup runs without needing root privileges for daily operation, which enhances security.



Portable and Organized: It's designed to live entirely on a mounted external SSD, typically at /mnt/ssd/. This keeps your main system clean and makes your AI setup portable. You just need to make sure the drive is formatted to ext4 to avoid potential driver issues.



User-Friendly Interface: While the setup process is straightforward, it is also highly specific and the steps must be followed carefully. The end result, however, is simple. You'll interact with your models through the clean web interface of AnythingLLM, which you can access in your browser. You can even swap out different AI models like you're building a "Pokemon team".


This guide will walk you through everything from the initial, one-time setup of your SSD and Podman configuration to the recurring commands for starting, stopping, and managing your AI containers. By the end, you'll have a fully functional system where you can chat with various language models, all hosted and controlled by you.
