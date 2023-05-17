project('udp-echo', 'c')

dpdk = dependency('libdpdk')
sources = files('src/main.c')
executable('udp-echo', sources, dependencies: dpdk)