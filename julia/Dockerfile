FROM julia:1.4

WORKDIR /usr/src/app

COPY server.jl Project.toml deps.jl ./

RUN julia deps.jl

CMD julia server.jl
