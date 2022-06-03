**Run**

touch echo "56000" > ~/.port_number_counter

**Create symlinks**

sudo ln -s /Users/<USERNAME>/scripts/aws-dev-tools/get_ports /usr/local/bin/
  
sudo ln -s /Users/<USERNAME>/scripts/aws-dev-tools/start_session /usr/local/bin/
  
sudo ln -s /Users/<USERNAME>/scripts/aws-dev-tools/connect /usr/local/bin/

**Connect to aws instance**
  
connect <instance-id> -> connect i-060713ea210043ai5
