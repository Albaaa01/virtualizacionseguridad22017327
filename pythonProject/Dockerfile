

# Pull Kali Linux OS from a Docker Hub repository
FROM kalilinux/kali-rolling


# Update the image
RUN apt-get update

# Install the following packages for our custom image
RUN apt-get install -y nmap
FROM jupyter/minimal-notebook:latest
# Set credentials for the root user, ROOT = all privileges, 21535220 = password
ENV USER root
ENV PASSWORD 22017327



# Expose ports for nmap and metasploit
EXPOSE 600 700

# Run the following commands when the container is created
CMD ["bash"]


