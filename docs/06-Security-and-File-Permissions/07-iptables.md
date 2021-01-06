#IPTABLES
  - Install iptables 
    ```
      sudo apt install iptables
    ```
    
  - Check rules
    ```
      sudo iptables -L
    ```
    
  ![iptables-1](../../images/iptables-1.png)

  - Drop rule
    ```
      sudo iptables -D INPUT/OUTPUT 1
    ```
