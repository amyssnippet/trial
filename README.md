# trial

## wsl install

```dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart```
```dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart```


## restart

## download ubuntu from microsoft store

1. set username admin123 and pass admin123
2. sudo apt update
3. sudo add-apt-repository ppa:deadsnakes/ppa
4. sudo apt update
5. sudo apt install python3.10 python3-pip
6. python3.10 -m pip install ray matplotlib pillow qiskit nibabel scipy scikit-image
7. ~/.local/bin/ray --version
8. ~/.local/bin/ray start --address="10.6.5.27:6379" --node-ip-address=10.6.5.27
9. ~/.local/bin/ray status
