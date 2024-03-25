# envoy-proxy

 docker build -t envoy-dynamic-fs-shk-img .

 docker run --rm -it -p 19000:19000 -p 10000:10000 envoy-dynamic-fs-shk-img     

 docker exec quizzical_lichterman sed -i 'www.httpbin.org' /var/lib/envoy/lds.yaml
