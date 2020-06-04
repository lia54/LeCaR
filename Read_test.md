
Citation:

    @inproceedings {216890,
    author = {Giuseppe Vietri and Liana V. Rodriguez and Wendy A. Martinez and Steven Lyons and Jason Liu and Raju Rangaswami and Ming Zhao and Giri Narasimhan},
    title = {Driving Cache Replacement with ML-based LeCaR},
    booktitle = {10th {USENIX} Workshop on Hot Topics in Storage and File Systems (HotStorage 18)},
    year = {2018},
    address = {Boston, MA},
    url = {https://www.usenix.org/conference/hotstorage18/presentation/vietri},
    publisher = {{USENIX} Association},
    month = jul,
    }


#### Code source

```python3 run.py <cache_size> lecar <trace_name>```

For instance, running 

```python3 run.py 50 lecar data.txt```\
```python3 run.py 50 lecar data.txt```\
```python3 run.py 50 lecar data.txt```

will produce the following output

```Results: lecar      size=50       hits=480, misses=20, ios=500, hitrate=96.0%, data.txt```

