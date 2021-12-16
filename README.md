# WRF-as-a-Service
Proof-of-Concept where I setup a webapp for users to input initial conditions and an email address, it runs the WRF for them, and then emails them a link to an S3 bucket with the output data.


# Notes

It appears that NCAR/WRF_DOCKER has already containerized the WRF, so that part of the project is mostly done. I just have to look it over and see how difficult it will be to convert between Namelist.input and a JSON/YAML.
