# REPO TUGAS KELOMPOK TCC
## Konsep
## Berbagai sofware IaaS
## Getting started PROXMOX  
Proxmox VE merupakan kependekan dari Proxmox Virtual Environment ada juga yang mengingkat menjadi PVE. Pengertian dari Proxmox VE adalah suatu platform virtualisasi yang stabil, lengkap, memiliki team support yang baik dan masuk di kelas virtualisasi enterprise. Proxmox ini merupakan proyek open source, dibangun dari Linux Debian. Proxmox VE akan melakukan manajeme container, virtual machine, storage, jaringan virtual, high availability cluster melalui antar muka web dan dapat juga menggunakan command line.  

PVE ini juga dikenal sebagai type hypervisor. Hypervisor ini merupakan aplikasi yang dapat melakukan manajemen virtual machine. Hypervisor dapat membuat virtual machine ,  melakukan konfigurasi virtual machine, menjalankan virtual machine dan juga mengendalikan virtual machine ini.  

Proxmox VE ini merupakan type 2 hypervisor. Type 2 hypervisor adalah hypervisor yang berjalan di atas operating system. Sedangkan type 1 hypervisor adalah hypervisor yang langsung menangani perangkat keras tanpa melalui operating system.  

Proxmox VE menggunakan Linux Debian karena Linux Debian mempertimbangkan release pada saat versi tersebut mencapai stability, security dan usability yang baik. Dengan demikan maka Proxmox VE mengandalkan Linux Debian dalam komitmentnya dalam stability, security, dan usability.  

Proxmox VE menyediakan teknologi virtualisasi yaitu  

1. KVM  
KVM merupakan kependekan dari Kernel Virtual Machine. KVM merupakan bagian integral dari Linux sejak tahun 2007.
Informasi lebih lanjut mengenai KVM silahkan mengunjungi http://www.linux-kvm.org/.  
2. QEMU  
QEMU menyediakan emulasi dan virtualisasi interface.
Informasi lebih lanjut mengenai QEMU dapat dibaca di http://www.qemu.org .  
3. LXC  
LXC atau Linux Container ini merupakan virtualisasi OS atau virtualisasi operating system. Di sini containernya diisolasi tetapi masih melakukan share pada operating system dan juga library/binnya.
Informasi lebih lanjut mengenai LXC silahkan mengunjungi https://linuxcontainers.org/ .
## Arsitektur dan konsep deplyment
