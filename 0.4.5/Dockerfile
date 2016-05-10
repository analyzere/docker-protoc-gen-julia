FROM julia:0.4.5

MAINTAINER oeuftete@gmail.com

RUN julia -e 'Pkg.update(); \
              Pkg.add("ProtoBuf");'

CMD ["sh", "/root/.julia/v0.4/ProtoBuf/plugin/protoc-gen-julia"]
