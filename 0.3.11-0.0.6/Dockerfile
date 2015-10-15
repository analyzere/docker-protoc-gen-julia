FROM julia:0.3.11

MAINTAINER oeuftete@gmail.com

RUN julia -e 'Pkg.update(); \
              Pkg.add("ProtoBuf"); \
              Pkg.pin("ProtoBuf", v"0.0.6");'

CMD ["sh", "/root/.julia/v0.3/ProtoBuf/plugin/protoc-gen-julia"]
