<h1>Bluetooth Prowler 📡</h1>
<img src="https://img.shields.io/badge/version-1.0.0-blue"></img> <img src="https://img.shields.io/badge/Python-%3E=%203.0-yellow"></img>
<h2>How to run</h2>

* Open a new terminal.
* Execute the following: `python3 bluetooth-prowler.py` (or the name of the file, if you renamed it)
* Choose an option from the menu.

<h2>How to use</h2>

Make sure Bluetooth is started and enabled before start.

<h3>Prowler mode:</h3>

Select `1` in the main menu for use this mode. `Prowler mode` scan for discoverable Bluetooth devices using `hcitool`. Scan again every ≈ 10 seconds. You can see the discoverable Bluetooth device MAC addresses. Finish with `CTRL + C`.

<h3>Intercept-attack mode:</h3>

Select `2` in the main menu for use this mode. `Intercept-attack mode` scan to find a specific MAC address.
* Enter the MAC address that you want to attack.
* If the address is not discoverable, the program retry after ≈ 5 seconds.
* If the address is found, the program start the attack after ≈ 3 seconds.
  
Finish with `CTRL + C`.
