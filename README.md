# cloudflared for OpenWRT

This is a derivative of the work by <a href="https://github.com/moetayuko/openwrt-cloudflared" target="_blank">moetayuko</a>, building <a href="https://github.com/cloudflare/cloudflared" target="_blank">cloudflared</a> using the Cloudflare <a href="https://github.com/cloudflare/go" target="_blank">fork</a> of the Go toolchain, with the only major difference being that the releases here will always be based on the latest version released by Cloudflare, rather than waiting for the maintainers of the OpenWRT package to release an update.

[![Build](https://github.com/sludgepudge/cloudflared-openwrt/actions/workflows/build.yml/badge.svg)](https://github.com/sludgepudge/cloudflared-openwrt/actions/workflows/build.yml)

## Why?

Myself and countless others rely on Cloudflare's Zero Trust service to manage connectivity between onsite and offsite devices/networks. Being up to date with Cloudflare is important to us and the official OpenWRT package for cloudflared can often be many weeks out of date, so this project was worked on.