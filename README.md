# nginx-autoinstall
BROTLI-PAGESPEED-GEOIP-FANCYINDEX-CACHEPURGE-HEADERMOD-SSL

<h2>Compatibility</h2>

- x86, x64, arm*
- Debian 8 and later
- Ubuntu 16.04 and later

<h2>Features</h2>
<ul>
<li> Latest mainline or stable version, from source
<li> Optional modules (see below)
<li> Removed useless modules
<li> Custom nginx.conf (default does not work)
<li> Init script for systemd (not provided by default)
<li> Logrotate conf (not provided by default)
<li> Block Nginx installation from APT using pinning, to prevent conflicts
</ul>

<h2>Optional modules/features</h2>
<ul>
<li>LibreSSL from source (CHACHA20, ALPN for HTTP/2, X25519, P-521)
<li>OpenSSL from source (TLS 1.3, CHACHA20, ALPN for HTTP/2, X25519, P-521)
<li>ngx_pagespeed (Google performance module)
<li>ngx_brotli (Brotli compression algorithm)
<li>ngx_headers_more (Custom HTTP headers)
<li>ngx_http_geoip2_module with libmaxminddb and GeoLite2 databases
<li>ngx_cache_purge (Purge content from FastCGI, proxy, SCGI and uWSGI caches)
<li>ngx-fancyindex (Fancy indexes module)
</ul>
