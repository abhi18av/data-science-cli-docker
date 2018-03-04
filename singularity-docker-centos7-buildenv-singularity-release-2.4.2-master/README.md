# singularity-docker-centos7-buildenv-singularity-release-2.4.2
centos7 build env for singularity/release-2.4.2

example Dockerfile provided for convenience.

Running without installation:
```
singularity run shub://truatpasteurdotfr/singularity-docker-centos7-buildenv-singularity-release-2.4.2
```
Building:
```
sudo singularity build singularity-docker-centos7-buildenv-singularity-release-2.4.2.simg  Singularity
```
Download and rename:
```
singularity pull --name "singularity-docker-centos7-buildenv-singularity-release-2.4.2" shub://truatpasteurdotfr/singularity-docker-centos7-buildenv-singularity-release-2.4.2
```
Running with a separate $HOME 
```
mkdir -p  ~/singularity.d/home/singularity-docker-centos7-buildenv-singularity-release-2.4.2
singularity run -H  ~/singularity.d/home/singularity-docker-centos7-buildenv-singularity-release-2.4.2 singularity-docker-centos7-buildenv-singularity-release-2.4.2.simg
```
