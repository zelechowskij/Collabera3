# Collabera3

Ansible playbook that returns manufacturer associated with MAC address


#How to use

## Requirements 
- Ansible

## Running

1. Clone the repository <br />
```git clone https://github.com/zelechowskij/Collabera3.git && cd Collabera3```<br />
2. **Place your API key in ```group_files/all/vars.yaml``` in the ```api_key``` field and save the file**<br />
3. Run the following with your custom MAC address:<br />
```ansible-playbook getMacAddr.yaml --extra-vars "mac=<MAC_ADDR>"```<br />
