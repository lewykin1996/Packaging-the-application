FROM ubuntu:22.04

RUN apt-get update && \
    apt-get install -y g++ clang && \
    rm -rf /var/lib/apt/lists/*

WORKDIR /app

COPY ConsoleApplication1/ConsoleApplication1.cpp .

CMD ["bash"]