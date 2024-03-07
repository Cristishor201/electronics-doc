<h1>I2C</h1>

I2C (TWI) - Inter-Integrated Circuit | Two Wire Interface

- conexiune rapida, ce permite conectarea dispozitivelor in lant (127 dispozitive maxim)
- viteza - 100 KHz

<img src="_img/i2c/i2c1.JPG" alt="Master - slave(s)" />

bidirectional = poate scrie catre slave si poate citit de la slave

informatia poate curge intr-o singura directie pe rand. half-duplex

SCL (serial Clock)
SDA (serial data)
GND

data = biti de comanda, citire de senzori, registri, etc.


<h2>Viteza scriere/citire:</h2>

<img src="_img/i2c/i2c2.JPG" alt="I2C Viteza" />

primele 3 sunt cele mai usor de integrat


<h2>Forma Semnal:</h2>

<img src="_img/i2c/semnal1.JPG" alt="semnal 1" />

<img src="_img/i2c/semnal2.JPG" alt="semnal 2" />

<img src="_img/i2c/semnal3.JPG" alt="semnal 3" />

(~ handshake protocol)

<img src="_img/i2c/semnal4.JPG" alt="semnal 4" />