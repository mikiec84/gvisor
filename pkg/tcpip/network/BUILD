load("//tools/go_stateify:defs.bzl", "go_test")

package(licenses = ["notice"])  # Apache 2.0

go_test(
    name = "ip_test",
    size = "small",
    srcs = [
        "ip_test.go",
    ],
    deps = [
        "//pkg/tcpip",
        "//pkg/tcpip/buffer",
        "//pkg/tcpip/header",
        "//pkg/tcpip/link/loopback",
        "//pkg/tcpip/network/ipv4",
        "//pkg/tcpip/network/ipv6",
        "//pkg/tcpip/stack",
        "//pkg/tcpip/transport/tcp",
        "//pkg/tcpip/transport/udp",
    ],
)
