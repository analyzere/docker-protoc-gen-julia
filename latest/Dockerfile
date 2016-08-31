FROM julia:latest

MAINTAINER techops@analyzere.com

RUN julia -e 'Pkg.update(); \
              Pkg.add("ProtoBuf");'

CMD ["sh", "/root/.julia/v0.4/ProtoBuf/plugin/protoc-gen-julia"]
