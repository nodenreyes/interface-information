1. create a virtual environment
cd ~/Documents
mkdir python_projects
cd python_projects
python3 -m venv venv

2. activate the environment
source venv/bin/activate

3. download this Libraries

pip install junos-eznc       # connect with Juniper devices via NETCONF
pip install lxml             # work with con XML
pip install pandas           # to work with tables and CSV
pip install pynetbox         # connect with NetBox vía API
pip install requests         # Dependency of pynetbox para HTTP
