Cars r rus startcode with queries and pageable
[![Java CI with Maven](https://github.com/MichaelDyvad/cars-startcode-queries/actions/workflows/maven.yml/badge.svg)](https://github.com/MichaelDyvad/cars-startcode-queries/actions/workflows/maven.yml)

How to setup a matching CI/CD pipeline
1. For at lave en CI/CD pipeline baseret på github action skal der oprettes et github repository.
2. Github repoet skal connectes med azure web service, så github action bliver brugt som en byggeserver
3. Der bliver oprettet en azure web service
4. Sproget java 11 bliver valgt under oprettelse, den gratis plan bliver valgt og north europe bliver valgt som område
5. Under deployment center i web servicen finder man sit oprettet repo og branch
6. 




For at kunne sætte denne spring boot app op med en database skal der sættes en virtuel maskine op, hvor der skal:
1. ssh nøgle
2. Connect ssh nøglen til ens virtuel maskine
3. installere docker på den virtuelle maskine
4. installere ubuntu
5. installere mysql, så der kan sættes en database op


