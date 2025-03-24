<h1 align="center"> KnowPhish [USENIX Security 2024]</h1>


This is the official repository of our [USENIX Security 2024](https://www.usenix.org/conference/usenixsecurity24) paper "[KnowPhish: Large Language Models Meet Multimodal Knowledge Graphs for Enhancing Reference-Based Phishing Detection](https://www.usenix.org/conference/usenixsecurity24/presentation/li-yuexin)".

## Updates
- [2025.01] [PhishIntel](https://arxiv.org/abs/2412.09057), our deployment-oriented phishing detection system built upon KnowPhish, is accepted by WWW 2025 (Demo).
- [2024.12] [PhishAgent](https://arxiv.org/abs/2408.10738), our new work built upon KnowPhish, is accepted by AAAI 2025 (Oral).
- [2024.11] We release the download link for the TR-OP dataset.


## Datasets
1. [TR-OP](https://www.dropbox.com/scl/fi/z1liysgw42g9apcsp1v3i/TR-OP.zip?rlkey=9ovjwzteon3gp6v1yff1pdjrt&st=ftefbkof&dl=0): A balanced evaluation dataset with 5000 benign webpages and 5000 phishing webpages.

## Codes
Thanks for your interest in our KnowPhish project! Our phishing detector is currently deployed in a commercial setting. Due to security considerations from our sponsors, we are unable to release the code or knowledge base at this time. As such, this GitHub repository serves as a host for the supplementary materials PDF and certain datasets. That said, I am more than happy to answer any questions you may have regarding our paper and its findings. Please feel free to reach out via email or raise an issue here. Thank you again for your attention!

## Citation
Please consider citing our papers if you find them useful:

- KnowPhish (USENIX Security 2024): 
```bibtex
@inproceedings {li2024knowphish,
  author = {Yuexin Li and Chengyu Huang and Shumin Deng and Mei Lin Lock and Tri Cao and Nay Oo and Hoon Wei Lim and Bryan Hooi},
  title = {{KnowPhish}: Large Language Models Meet Multimodal Knowledge Graphs for Enhancing {Reference-Based} Phishing Detection},
  booktitle = {33rd USENIX Security Symposium (USENIX Security 24)},
  year = {2024},
  isbn = {978-1-939133-44-1},
  address = {Philadelphia, PA},
  pages = {793--810},
  url = {https://www.usenix.org/conference/usenixsecurity24/presentation/li-yuexin},
  publisher = {USENIX Association},
  month = aug
}
```
- PhishAgent (AAAI 2025):
```bibtex
@misc{cao2025phishagentrobustmultimodalagent,
    title={PhishAgent: A Robust Multimodal Agent for Phishing Webpage Detection}, 
    author={Tri Cao and Chengyu Huang and Yuexin Li and Huilin Wang and Amy He and Nay Oo and Bryan Hooi},
    year={2025},
    eprint={2408.10738},
    archivePrefix={arXiv},
    primaryClass={cs.CR},
    url={https://arxiv.org/abs/2408.10738}, 
}
```
- PhishIntel (WWW 2025 Demo):
```bibtex
@misc{li2024phishintel,
    title={PhishIntel: Toward Practical Deployment of Reference-based Phishing Detection},
    author={Yuexin Li and Hiok Kuek Tan and Qiaoran Meng and Mei Lin Lock and Tri Cao and Shumin Deng and Nay Oo and Hoon Wei Lim and Bryan Hooi},
    year={2025},
    eprint={2412.09057},
    archivePrefix={arXiv},
    primaryClass={cs.CR},
    url={https://arxiv.org/abs/2412.09057}, 
}
```
