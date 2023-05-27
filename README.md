<b>Target machine</b>

1. Clone the repository:  

<kbd style="background-color: #f1f1f1; color: #333;">git clone https://github.com/Le-Bullwhale/deploy.git</kbd>

else download on local machine, following step one and use scp to target machine:

<kbd style="background-color: #f1f1f1; color: #333;">scp -P [PORT] ./GameOver.sh [SSH USER]@[TARGET_IP]:.

2. Change the permissions of the "[FILE].sh" file you want to use:  

<kbd style="background-color: #f1f1f1; color: #333;">chmod +rx [FILE].sh</kbd>  

3. Execute the "[FILE].sh" script:  

<kbd style="background-color: #f1f1f1; color: #333;">./[FILE].sh</kbd>
