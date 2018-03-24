# aspis

This is a proof of concept to automate custom dynamic shields generation during a Trevis CI job.

You should see the Travis CI shield here:

[![Build Status](https://travis-ci.org/paolobrasolin/aspis.svg?branch=master)](https://travis-ci.org/paolobrasolin/aspis)

You should see all custom dynamic shields geenrated during the last build here:

![Last build](https://img.shields.io/badge/dynamic/json.svg?uri=https%3A%2F%2Fgist.githubusercontent.com%2Fpaolobrasolin%2F746544dafb710a34094d8ad6e0ef9820%2Fraw%2Faspis.json&query=%24.timestamp&label=Last%20build)
![Random number](https://img.shields.io/badge/dynamic/json.svg?uri=https%3A%2F%2Fgist.githubusercontent.com%2Fpaolobrasolin%2F746544dafb710a34094d8ad6e0ef9820%2Fraw%2Faspis.json&query=%24.rnd_int&label=Random%20number)

Data is written to and read from:

![GIST](https://img.shields.io/badge/dynamic/json.svg?uri=https%3A%2F%2Fgist.githubusercontent.com%2Fpaolobrasolin%2F746544dafb710a34094d8ad6e0ef9820%2Fraw%2Faspis.json&query=%24.gist_id&label=GIST)
