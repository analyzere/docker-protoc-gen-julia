FROM julia:0.6.0

MAINTAINER techops@analyzere.com

RUN julia -e 'Pkg.update(); \
              Pkg.add("ProtoBuf");'

CMD ["sh", "/root/.julia/v0.6/ProtoBuf/plugin/protoc-gen-julia"]
