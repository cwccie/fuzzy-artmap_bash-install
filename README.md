# fuzzy-artmap_bash-install

- This bash file will install Fuzzy ARTMAP python and associated dependencies

- The included Bash file (famsetup.sh) is meant to install Fuzzy ARTMAP (FAM) on Linux. This bash file was tested on a new install of Ubuntu 22.04 server via CLI.
- Ubuntu Server 22.04 can be downloaded here: https://releases.ubuntu.com/22.04.3/ubuntu-22.04.3-live-server-amd64.iso
- Follow the steps below and be aware that this bash file does include an option for Samba setup, which can be useful if you intend to use local datasets.

# Install Steps

Step 1 - Navigate to the folder you would like to install the FAM environment and execute the following sudo nano command sudo nano famsetup.sh

Step 2 - Paste Bash File Text into nano. Read and understand the code and comments before using

Step 3 - Write and exit nano (Ctr-X, Y, enter)

Step 4 - Execute the following 2 commands

sudo chmod +x famsetup.sh # Make the script executable 
sudo ./famsetup.sh # Run the script

# Validation

Successful completion will produce an output similar to the following:

2024-01-18 16:38:24,480 - fuzzy_artmap.fuzzy_artmap_distributed_gpu - INFO - worker params: committed beta = 0.75

2024-01-18 16:38:24,480 - fuzzy_artmap.fuzzy_artmap_distributed_gpu - INFO - f1_size: 4, f2_size:1, committed beta = 0.75

2024-01-18 16:38:24,480 - fuzzy_artmap.fuzzy_artmap_distributed_gpu - INFO - Workers initialized

2024-01-18 16:38:24.480519

tensor([[1., 0.]])

tensor([[0., 1.]])

elapsed: 0:00:00.748817- 2024-01-18 16:38:25.229336

Counter({True: 917, False: 83})

torch.Size([51, 4])

torch.Size([51, 2])

tensor(18)
