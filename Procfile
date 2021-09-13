web: cat x* > alpine.qcow2 && rm -rf x* && qemu-system-x86_64 --enable-kvm -m 256 --display none -redir tcp:22::22 alpine.qcow2 & wssh --port=$PORT --redirect=False --address=localhost
