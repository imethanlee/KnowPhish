<h1 align="center"> KnowPhish [USENIX Security 2024]</h1>


This is the official repository of our [USENIX Security 2024](https://www.usenix.org/conference/usenixsecurity24) paper "[KnowPhish: Large Language Models Meet Multimodal Knowledge Graphs for Enhancing Reference-Based Phishing Detection](https://www.usenix.org/conference/usenixsecurity24/presentation/li-yuexin)".

## Updates
- [2025.01] [PhishIntel](https://dl.acm.org/doi/10.1145/3701716.3715192), our deployment-oriented phishing detection system built upon KnowPhish, is accepted by WWW 2025 (Demo).
- [2024.12] [PhishAgent](https://ojs.aaai.org/index.php/AAAI/article/view/35003), our new work built upon KnowPhish, is accepted by AAAI 2025 (Oral).
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
  title = {{KnowPhish}: Large Language Models Meet Multimodal Knowledge Graphs for Enhancing {Reference-Based} Phishing Detection},
  author = {Yuexin Li and Chengyu Huang and Shumin Deng and Mei Lin Lock and Tri Cao and Nay Oo and Hoon Wei Lim and Bryan Hooi},
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
@article{cao2025phishagent,
  title={PhishAgent: A Robust Multimodal Agent for Phishing Webpage Detection},
  author={Cao, Tri and Huang, Chengyu and Li, Yuexin and Huilin, Wang and He, Amy and Oo, Nay and Hooi, Bryan},
  volume={39},
  url={https://ojs.aaai.org/index.php/AAAI/article/view/35003},
  DOI={10.1609/aaai.v39i27.35003},
  number={27},
  journal={Proceedings of the AAAI Conference on Artificial Intelligence},
  year={2025},
  month={Apr.},
  pages={27869-27877}
}
```
- PhishIntel (WWW 2025 Demo):
```bibtex
@inproceedings{li2025phishintel,
  title = {PhishIntel: Toward Practical Deployment of Reference-Based Phishing Detection},
  author = {Li, Yuexin and Tan, Hiok Kuek and Meng, Qiaoran and Lock, Mei Lin and Cao, Tri and Deng, Shumin and Oo, Nay and Lim, Hoon Wei and Hooi, Bryan},
  year = {2025},
  isbn = {9798400713316},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://doi.org/10.1145/3701716.3715192},
  doi = {10.1145/3701716.3715192},
  booktitle = {Companion Proceedings of the ACM on Web Conference 2025},
  pages = {2863–2866},
  numpages = {4},
  keywords = {phishing detection system, real-time systems, task queue},
  location = {Sydney NSW, Australia},
  series = {WWW '25}
}
```
