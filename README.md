# WinVirtioISO
An ISO version of https://github.com/virtio-win/kvm-guest-drivers-windows

Was created in debian after cloning: https://github.com/virtio-win/kvm-guest-drivers-windows

with the command: genisoimage -v -J -r -V virtio_drivers -o win_virtio_drivers.iso kvm-guest-drivers-windows

which was availible after installing: genisoimage via 'apt-get install genisoimage'
