EECS 570 Intel SGX
------------------

This repository has code for EECS 570 group project called "TMIS(The Most Impenetrable Castle): Genome Sequencing with Side-Channel Attack Protection inside INTEL SGX".

For Intel(R) Software Guard Extensions for Linux\* OS, download the source code and prepare the submodules and prebuilt binaries:
```
   $ git clone https://github.com/intel/linux-sgx.git

Follow the steps for installing Intel SGXSDK, PSW and DCAP drivers.

Please ensure you are installing on a windows system or linux OS as Intel SGX is not supported on Mac OS or virtual machine. 
Furthermore remember to to enable Intel SGX in BIOS settings.

After that, this repository can be used to running Sample Code of Genome Sequencing with Side-Channel Attack Protection inside INTEL SGX.

Our sample codes are as follows:

1. StandaloneWS: Genome Sequencing code without enclave and side channel protection

2. StandaloneS: Genome Sequencing code without enclave 
  
3. EWS: Enclave without side channel protection	
		
4. ES:Enclave with side channel protection
	      
5. ESE:Enclave with side channel protection using encrypted input	

Individual sample code directories have their README files for further assistance.

Thank you.