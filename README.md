# ICMP_ECHO
This dataset is comprised on ICMP ECHO replies and responses between nodes on a testbed topology. Each IP address pair has 5000 exchanges.

10-31-22

The datasets presented in this repository have been created as a newer alternative to historically used datasets.

These datasets are curated in the sense that they are balanced with each having nearly the exact same number of samples for each class.

They are currently provided in pcap format which can be opened and if necessary converted, by Wireshark.

Additional datasets will be brought online periodically.


#ICMP Specific

The ICMP datasets listed here were created by PINGing between all of the testbed nodes in the topology and their default gateways.

For example, 172.16.11.1 would PING the following addresses:

172.16.11.99, 172.16.11.254, 172.16.22.1, 172.16.22.254, 172.16.33.1, 172.16.33.254, 172.16.44.1, 172.16.44.254

Each destination was "PINGed" 5000 times resulting in 5000 ICMP type 8 and 5000 ICMP type 0 messages.
  
Each dataset has 80000 total samples. Example classes might include IP address and type combinations.

These datasets can also be merged with other datasets in this repository.
  
The file name 11-1-correct means that the datasets was verified to include the desired traffic and that it is balanced.


#CITATIONS

If citing these datasets, please use the following:

@Article{RIT-Network-Datasets,
  author  = {Bruce Hartpence, Andres Kwasinski, Daryl Johnson, Bill Stackpole},
  journal = {},
  title   = {},
  year    = {2022},
  volume  = {},
  number  = {},
  pages   = {},
  doi     = {10.57673/gccis-yg55}
}

DOI URL: www.doi.org/10.57673/gccis-yg55
