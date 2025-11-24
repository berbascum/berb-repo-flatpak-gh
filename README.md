# Berbascum's flatpak repo on github

This contains some custom flatpak builds. Often there are testing packages.

The docs subdir contains the root of the flatpak repo, which is the
published dir in the Github Pages.

## Adding the repo
Add the flatpack repo:
<flatpak remote-add --gpg-import=flatberb-pub.gpg --user flatberb https://berbascum.github.io/berb-repo-flatpak-gh>

## Applications

In the repository, currently there are two packages:

### Android Translation Layer BaseApp (Depends):
- org.gnome.Platform 48

### NewPipe 0.28.0
- org.gnome.Platform 48
- org.freedesktop.Platform.GL.default  25.2.6  24.08
- org.freedesktop.Platform.GL.default  25.2.6  24.08extra
- org.freedesktop.Platform.ffmpeg-full         24.08
- If ffmpeg full is not installed, do manually (to avoid missing aac codec):
<flatpak install org.freedesktop.Platform.ffmpeg-full//24.08>
