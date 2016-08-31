FROM julia:0.4.6

MAINTAINER oeuftete@gmail.com

RUN julia -e 'Pkg.update(); \
              Pkg.add("ProtoBuf"); \
              Pkg.pin("ProtoBuf", v"0.1.4");'

CMD ["sh", "/root/.julia/v0.4/ProtoBuf/plugin/protoc-gen-julia"]
