# dht11-json
Pump DHT11 data through a Raspberry Pi. Output a JSON

You need wiringPi lib. Assuming your lib is installed in /usr/local/lib, you can build it typing:

    cc -o bin/dht11 dht11.c -L/usr/local/lib -lwiringPi
