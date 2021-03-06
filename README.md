# Spring Shell Log Access Parser Sample

## What is this?


This example shows how to use the Spring Shell tool to parse an access log file. It is also possible to perform queries with totalization of accesses by ip, with a threshold and date period.


## Used Tools

*   [SPRING INITIALIZR](https://start.spring.io)

*   [Spring Boot](http://projects.spring.io/spring-boot)

*   [Spring Shell](https://projects.spring.io/spring-shell)

*   [Spring Data JPA](https://projects.spring.io/spring-data-jpa)

*   [Maven](https://maven.apache.org)



## Starting...

mvn spring-boot:run

After start, type help to list all commands.

### Commands

        clean: clear all data rows on database
        count: count data rows on database
        load: Load data file. Example: load path-to-log-file
        parse: Parse the log file and search data. Example: parse path-to-log-file start-date(in yyyy-MM-dd.HH.mm.ss format) duration(hourly or daily) threshold(greather than 0)
        query: Search data from database. Example: query start-date(in yyyy-MM-dd.HH.mm.ss format) duration(hourly or daily) threshold(greather than 0)

## Continuous Integration

### Codeship

[ ![Codeship Status for jonyfs/spring-boot-shell-log-parser](https://app.codeship.com/projects/770d74c0-f628-0135-cc1d-16cf1470df95/status?branch=master)](https://app.codeship.com/projects/274265)

### TravisCI
[![Build Status for jonyfs/spring-boot-shell-log-parserapi](https://travis-ci.org/jonyfs/spring-boot-shell-log-parser.svg?branch=master)](https://travis-ci.org/jonyfs/spring-boot-shell-log-parser)


## Code Quality

### Codebeat
[![codebeat badge](https://codebeat.co/badges/cd95d2e0-4db8-4090-b4c4-c2a5504f9ccf)](https://codebeat.co/projects/github-com-jonyfs-spring-boot-shell-log-parser-master)

### Codecov
[![codecov](https://codecov.io/gh/jonyfs/spring-boot-shell-log-parser/branch/master/graph/badge.svg)](https://codecov.io/gh/jonyfs/spring-boot-shell-log-parser)

### Codacy

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/6c961da94ce044399b6f95e3b0c26c9f)](https://www.codacy.com/app/jonyfs/spring-boot-shell-log-parser?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=jonyfs/spring-boot-shell-log-parser&amp;utm_campaign=Badge_Grade)

### Code Climate
[![Maintainability](https://api.codeclimate.com/v1/badges/b66ddd668d657a4457aa/maintainability)](https://codeclimate.com/github/jonyfs/spring-boot-shell-log-parser/maintainability)

[![Test Coverage](https://api.codeclimate.com/v1/badges/b66ddd668d657a4457aa/test_coverage)](https://codeclimate.com/github/jonyfs/spring-boot-shell-log-parser/test_coverage)

### CodeScene
[![](http://codescene.io/projects/2438/status.svg)](http://codescene.io/projects/2438/jobs/latest-successful/results)

### Sonar
[![Quality Gate](https://sonarcloud.io/api/project_badges/quality_gate?project=br.com.jonyfs%3Aparser)](https://sonarcloud.io/dashboard?id=br.com.jonyfs%3Aparser)

[![Security](https://sonarcloud.io/api/project_badges/measure?project=br.com.jonyfs%3Aparser&metric=security_rating)](https://sonarcloud.io/dashboard?id=br.com.jonyfs%3Aparser)

[![Maintainability](https://sonarcloud.io/api/project_badges/measure?project=br.com.jonyfs%3Aparser&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=br.com.jonyfs%3Aparser)


[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=br.com.jonyfs%3Aparser&metric=coverage)](https://sonarcloud.io/dashboard?id=br.com.jonyfs%3Aparser)


### Dependency Badge

[![Dependency Status](https://beta.gemnasium.com/badges/github.com/jonyfs/spring-boot-shell-log-parser.svg)](https://beta.gemnasium.com/projects/github.com/jonyfs/spring-boot-shell-log-parser)


