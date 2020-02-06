# Network Intrusion Detection (Classification)
## BUSINESS PROBLEM:
Build a network intrusion detection system to detect anamolies and attacks in the network. There are two problems. 
- **Binomial Classification:** Activity is normal or attack.
- **Multinomial Classification:** Activity is normal or DOS or PROBE or R2L or U2R Please note that, currently the dependent variable (target variable) is not definied explicitly. However, you can use attack variable to define the target variable as required. DATA AVAILABILITY: This data is [KDDCUP’99 data set](https://www.dropbox.com/s/1vg9ljk9auicna0/3.%20Network%20Intrusion%20Detection%20System.zip?dl=0), which is widely used as one of the few publicly available data sets for network-based anomaly detection systems.
### LIST OF COLUMNS FOR THE DATA SET: 
**["duration","protocol_type","service","flag","src_bytes","dst_bytes","land", "wrong_fragment","urgent","hot","num_failed_logins","logged_in", "num_compromised","root_shell","su_attempted","num_root","num_file_creations", "num_shells","num_access_files","num_outbound_cmds","is_host_login", "is_guest_login","count","srv_count","serror_rate", "srv_serror_rate", "rerror_rate","srv_rerror_rate","same_srv_rate", "diff_srv_rate",**
