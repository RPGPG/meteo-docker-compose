Docker-compose-ready system to retrieve data from https://danepubliczne.imgw.pl/api/data/synop
It uses 2 images from Docker Hub - pgul/meteo-html for presentation (Nginx) and pgul/meteo-cron to run Python scripts

#setup
docker-compose up -d
Default port web access is :2342

Maps are updated at [hh]:15, charts after [hh]:16
Charts have placeholder data until 24 hours of operation.
