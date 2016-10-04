FROM julia:0.5.0

MAINTAINER techops@analyzere.com

RUN julia -e 'Pkg.update(); \
              Pkg.add("ProtoBuf");'

CMD ["sh", "/root/.julia/v0.5/ProtoBuf/plugin/protoc-gen-julia"]
