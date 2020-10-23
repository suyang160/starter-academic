+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Research Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "A decentralized IoT identity management system based on blockchain"
  company = "Demo video"
  company_url = ""
  location = "Shanghai,China"
  date_start = "2019-09-01"
  date_end = "2020-02-01"
  description = """
  
  * Designed smart contracts on Ethereum platform and combine IPFS to achieve the process of creating,restoring,deleting of the DID (Decentralized Identifiers) of IoT devices.
  * Designed a IoT device prototype based on LPC55S69 (MCU, produced by NXP company), ESP32 module (WiFi), HC05 module (BlueTooth). LPC55S69 has the Peripherals such as PUF (Physical Unclonable Functions), TRNG (True Random Number Generator) and TrustZone which could be used to protect the security of DID.
  * Developed an app based on Android which could be used to generate the DID of user and communicate with IoT device through Bluetooth to trigger it to generate DID.
  """

[[experience]]
  title = "Charging payment system based on blockchain"
  company = "Demo video"
  company_url = ""
  location = "Shanghai,China"
  date_start = "2018-07-01"
  date_end = "2019-02-01"
  description = """

  *This is a POC project cooperating with BMW company, which aims at using the blockchain technology to explore the new payment method in charging scenario of electrical vehicles.*
  * Set up a private chain through ethereum, and wrote the code of smart contracts on it to complete the deduction of charging payment.
  * Transformed an commercial charging pile and added a raspberry pi 3B+ in it as the controller to control the start and stop of charging. The program was written in python. There was also a raspberry pi in the electrical vehicle.
  * Designed and coded the interactive process between the charging pile and electrical vehicle, In short, When the car drived close to the charging pile, they would communicate through the bluetooth. The car would pay enough deposit to the address of contract, the charging pile would verify it and start charging. After the finish of charging, the charging pile would pay back the redundant deposit.
  * Designed a charging pile background management system based on Django and Bootstrap which can get the GPS information and the charging state of charging pile.
  """

[[experience]]
  title = "Medically assisted evaluation devices"
  company = "Demo video"
  company_url = ""
  location = "Shanghai,China"
  date_start = "2017-09-01"
  date_end = "2018-01-01"
  description = """
  *The interns need to practice on the simulation baby about cardiopulmonary resuscitation (CPR) and the operation of the oxygen bottle. Current evaluation method is by experienced doctor, the project aims at using extra devices to evaluate the intern’s operation.*
  * Designed the PCB of the device, and choosed relevant chips mainly including CC2640R2F(BLE chip produced by TI),BMP180(air pressure detection),Thin film pressure sensor.
  * Wrote programs on the CC2640R2F to drive the BMP180 to get the raw data of air pressure and wrote the data into the corresponding BLE air pressure service.
  * Developed an app based on android which could discover and connect our BLE device, search the air pressure service to get the raw data and then handle it to get the actual pressure data.
  
  """

+++
