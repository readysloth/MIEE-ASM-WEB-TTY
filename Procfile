web: export LD_LIBRARY_PATH=/app/.apt/lib/x86_64-linux-gnu:/app/.apt/usr/lib/x86_64-linux-gnu && cat x* > alpine.qcow2 && rm -rf x* && qemu-system-x86_64 -m 256 --display none -net user,hostfwd=tcp::22:22 alpine.qcow2 & wssh --port=$PORT --redirect=False --address=localhost
