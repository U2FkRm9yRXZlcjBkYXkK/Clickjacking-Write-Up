# Clickjacking-Write-Up
simple write-up,  clickjack,  vulnerability 

Clickjacking vulnerability allows an attacker to trick users into performing accidental clicks on a victim application/website interface by embedding the target page within an iframe on a deceptive page and controlling the layers/click location.

# Well how do you find out this?
1. scan with nikto
`nikto -h https://[target].com/`

result:
<img width="588" height="25" alt="Screenshot 2025-10-08 045253" src="https://github.com/user-attachments/assets/c934af0d-ac71-4fc6-9d9a-d972af810aff" />

3. use poc to confirm
