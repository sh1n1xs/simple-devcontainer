# Use Arch Linux base image (if you don't need AUR packages)
# FROM archlinux:latest

# Use Arch Linux base image w/ AUR
FROM greyltc/archlinux-aur:yay

# Update package lists (recommended before installing anything)
RUN pacman -Syu --noconfirm

# Install base stuff
RUN pacman -S --noconfirm bash make git

#---------------------------------------------------------------------------------------------------------------------#
# uncomment as needed

# install python stuff
#RUN pacman -S --noconfirm python python-pip

# install RUST stuff
#RUN pacman -S --noconfirm rust

# install dotnet (C#) stuff
#RUN pacman -S --noconfirm dotnet-sdk dotnet-runtime aspnet-runtime

# install js stuff
#RUN pacman -S --noconfirm nodejs npm

#---------------------------------------------------------------------------------------------------------------------#

# install regular stuff
#RUN pacman -S --noconfirm YOURPACKAGE

# install a AUR pkg
# RUN sudo -u ab -D~ bash -c 'yay -Syu --removemake --needed --noprogressbar --noconfirm YOURAURPACKAGE'
