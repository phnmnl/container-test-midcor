FROM container-registry.phenomenal-h2020.eu/phnmnl/midcor:latest
MAINTAINER PhenoMeNal-H2020 Project ( phenomenal-h2020-users@googlegroups.com )

# get the data
RUN wget "https://drive.google.com/uc?export=download&id=0B2e3YmwhK4fkeW1ORld3ZVZ2ZDQ" -O midcor_outin_input.csv
RUN runMidcor.R -i midcor_outin_input.csv -o output.csv
# we are currently not testing for the correctness of the run, but at least we know that is running without issues.
