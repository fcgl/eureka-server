# Eureka Server

## Git Steps
1. Fork Branch
2. Open terminal and clone **forked branch**: `git clone https://github.com/<YOUR USERNAME>/eureka-server.git`
3. Go inside templates directory: `cd templates`
3. Add upstream repo: `git remote add upstream https://github.com/fcgl/eureka-server.git`
4. Confirm that you have an origin and upstream repos: `git remote -v`

## Build & Run App

This template should work for both macOS and Linux

1. Download docker for your operating system
2. From project root run the following commands:
    * **Build:** `docker build -t eurekaserver .`
    * **Run:** `docker run -d=true -p 8761:8761 eurekaserver`

