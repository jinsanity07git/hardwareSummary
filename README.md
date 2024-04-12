# hardwareSummary
Extracting and Fetching all system and hardware information such as os details, CPU and GPU information, disk and network usage in Python using platform, psutil and gputil libraries.



### CPU collection

| Brand                         | CPU                                            | Arch   | OS      | Benchmarking | Comb                                                         | Score |
| ----------------------------- | ---------------------------------------------- | ------ | ------- | ------------ | ------------------------------------------------------------ | ----- |
| TC17                          | Intel(R) Core(TM) i9-14900KF                   | AMD64  | Windows | 15.654       | Core-i9-14900KF                                              | 39.25 |
| Dell Precision 3561           | 11th Gen Intel(R) Core(TM) i7-11800H @ 2.30GHz | AMD64  | Windows | 23.852       | Core-i7-11800H                                               | 13.47 |
| WUYING: 8 vCPU / 16 GiB Linux | Intel(R) Xeon(R) Platinum 8163 CPU @ 2.50GHz   | x86_64 | Linux   | 33.572       | [Xeon-Platinum-8163](https://versus.com/en/intel-xeon-gold-6126-vs-intel-xeon-platinum-8168) |       |
|                               | Intel(R) Xeon(R) Gold 6126 CPU @ 2.60GHz       | x86_64 | Linux   | 38.685       | [Xeon-Gold-6126](https://technical.city/en/cpu/Xeon-Gold-6126) | 12.21 |
|                               | Intel(R) Xeon(R) CPU E5-2643 v4 @ 3.40GHz      | AMD64  | Windows | 39.258       | Xeon-E5-2643-v4                                              | 7.62  |
| google colab free tier        | Intel(R) Xeon(R) CPU @ 2.20GHz                 | x86_64 | Linux   | 43.078       |                                                              |       |
|                               | Intel(R) Xeon(R) Gold 6126 CPU @ 2.60GHz       | AMD64  | Windows | 62.969       |                                                              |       |
| Oracle 1G-1G-0.5Gbps          | AMD EPYC 7551 32-Core Processor                | x86_64 | Linux   | 98.732       | EPYC-7551                                                    | 14.67 |



### GPU collection

```
!git clone https://github.com/jinsanity07git/hardwareSummary
!python hardwareSummary/hardware.py
```



| id    | name                   | total memory | Synthetic benchmark | CUDA API |
| ----- | ---------------------- | ------------ | ------------------- | -------- |
| colab | Tesla T4               | 15360.0MB    | 28.16               | 70627    |
| dell  | NVIDIA T600 Laptop GPU | 4096.0MB     | 16.69               | 26600    |



Performance source

* https://technical.city/en/video/Tesla-T4-vs-T600
