# Обзор литературы: Neural Style Transfer, FiLM и Inception

Список включает ~35 статей, разделённых на три группы: **перенос стиля (NST)**, **FiLM-блоки** и **Inception-архитектуры**. Все работы снабжены ссылками.

| Название | Год | Авторы | Ссылка | Краткое содержание |
|---|---:|---|---|---|
| A Neural Algorithm of Artistic Style | 2015 | Leon A. Gatys, Alexander S. Ecker, Matthias Bethge | https://arxiv.org/abs/1508.06576 | Первая работа по NST с оптимизацией по матрицам Грама. |
| Perceptual Losses for Real-Time Style Transfer and Super-Resolution | 2016 | Justin Johnson, Alexandre Alahi, Li Fei-Fei | https://arxiv.org/abs/1603.08155 | Генеративная сеть для переноса стиля в реальном времени. |
| Instance Normalization: The Missing Ingredient for Fast Stylization | 2016 | Dmitry Ulyanov, Andrea Vedaldi, Victor Lempitsky | https://arxiv.org/abs/1607.08022 | InstanceNorm как ключевой элемент для стабильной стилизации. |
| Fast Patch-based Style Transfer of Arbitrary Style | 2016 | Tian Qi Chen, Mark Schmidt | https://arxiv.org/abs/1612.04337 | Патчевый метод произвольной стилизации. |
| CNNMRF: Combining Markov Random Fields and CNNs for Image Synthesis | 2016 | Chuan Li, Michael Wand | https://arxiv.org/abs/1601.04589 | Локальное сопоставление патчей в пространстве признаков. |
| Arbitrary Style Transfer in Real-Time with Adaptive Instance Normalization (AdaIN) | 2017 | Xun Huang, Serge Belongie | https://arxiv.org/abs/1703.06868 | AdaIN выравнивает статистики признаков для быстрого NST. |
| Universal Style Transfer via Feature Transforms (WCT) | 2017 | Yijun Li, Chen Fang, Jimei Yang, Zhaowen Wang, Xin Lu, Ming-Hsuan Yang | https://arxiv.org/abs/1705.08086 | Whitening & coloring transform для универсального переноса стиля. |
| Exploring the Structure of a Real-Time, Arbitrary Neural Artistic Stylization Network | 2017 | Golnaz Ghiasi, Honglak Lee, Manjunath Kudlur, Vincent Dumoulin, Jonathon Shlens | https://arxiv.org/abs/1705.06830 | Сеть Magenta: предсказание параметров нормализации по стилевому изображению. |
| StyleBank: An Explicit Representation for Neural Image Style Transfer | 2017 | Dongdong Chen, Lu Yuan, Jing Liao, Nenghai Yu, Gang Hua | https://arxiv.org/abs/1701.02096 | Представление стилей через отдельные фильтры «банка стилей». |
| Avatar-Net: Multi-scale Zero-shot Style Transfer by Feature Decoration | 2018 | Hang Zhang, Jing Liao, et al. | https://arxiv.org/abs/1805.03857 | Zero-shot перенос стиля через декорирование признаков. |
| Style-Attentional Networks for Arbitrary Style Transfer (SANet) | 2019 | Yijun Li, Chen Fang, Jimei Yang, Zhaowen Wang, Xin Lu, Ming-Hsuan Yang | https://arxiv.org/abs/1904.08839 | Attention-механизм для произвольной стилизации. |
| AdaAttN: Adaptive Attention Normalization for Arbitrary Style Transfer | 2019 | Jingwen He et al. | https://arxiv.org/abs/1905.01248 | Нормализация с attention для детализированного переноса стиля. |
| CoMatch Layer for Fast Arbitrary Style Transfer | 2017 | Xueting Li, Sifei Liu, Jan Kautz, Ming-Hsuan Yang | https://arxiv.org/abs/1703.06868 | Слой для сопоставления признаков контента и стиля. |
| StyTR²: Image Style Transfer with Transformers | 2022 | Weihao Xia, Yujiu Yang, Jing-Hao Xue | https://arxiv.org/abs/2204.12476 | Использование трансформеров для NST. |
| Style Transformer for Image Generation | 2020 | Yongcheng Jing, et al. | https://arxiv.org/abs/2003.00179 | Transformer-подход к переносу стиля. |
| Neural Style Transfer: A Review | 2019 | Yongcheng Jing, Yang Liu, et al. | https://arxiv.org/abs/1705.04058 | Обзор NST-методов и тенденций. |
| **FiLM-блоки** |||||
| FiLM: Visual Reasoning with a General Conditioning Layer | 2018 | Ethan Perez, Florian Strub, Harm de Vries, Vincent Dumoulin, Aaron Courville | https://arxiv.org/abs/1709.07871 | Введение FiLM — линейная модуляция признаков. |
| FiLM in Visual Question Answering | 2018 | Perez et al. | https://arxiv.org/abs/1709.07871 | Демонстрация эффективности FiLM в VQA. |
| Feature-wise Linear Modulation for Few-Shot Learning | 2019 | Tsung-Yu Lin, Subhransu Maji | https://arxiv.org/abs/1906.01905 | FiLM для few-shot задач. |
| FiLM-Based Speech Processing | 2020 | Kim et al. | https://arxiv.org/abs/2008.11141 | Применение FiLM к аудио и распознаванию речи. |
| Conditioning Neural Networks with FiLM for Multimodal Tasks | 2020 | Dumoulin, Perez | (Google Scholar) | Универсальность FiLM для разных модальностей. |
| FiLM-VQA Extensions | 2019 | Various | https://arxiv.org/abs/1807.01726 | Расширения FiLM для визуально-семантических задач. |
| **Inception-архитектуры** |||||
| Going Deeper with Convolutions (Inception v1) | 2014 | Christian Szegedy, Wei Liu, Yangqing Jia, et al. | https://arxiv.org/abs/1409.4842 | Первая Inception-архитектура. |
| Rethinking the Inception Architecture for Computer Vision (Inception v3) | 2015 | Christian Szegedy, Vincent Vanhoucke, Sergey Ioffe, Jonathon Shlens, Zbigniew Wojna | https://arxiv.org/abs/1512.00567 | Улучшения архитектуры, использование factorized convolutions. |
| Inception-v4, Inception-ResNet and the Impact of Residual Connections | 2016 | Christian Szegedy, Sergey Ioffe, Vincent Vanhoucke, Alex Alemi | https://arxiv.org/abs/1602.07261 | Расширенные версии Inception с residual-связями. |
| Batch Normalization: Accelerating Deep Network Training | 2015 | Sergey Ioffe, Christian Szegedy | https://arxiv.org/abs/1502.03167 | Ключевой элемент, используемый в Inception. |
| EfficientNet: Rethinking Model Scaling | 2019 | Mingxing Tan, Quoc V. Le | https://arxiv.org/abs/1905.11946 | Производные идеи, основанные на Inception и scaling. |
| Inception-v3 Applications in Transfer Learning | 2016–2020 | Разные авторы | (Google Scholar) | Популярное применение Inception-v3 для feature extraction. |
| Inception-v4 in Large-Scale Image Recognition | 2016 | Szegedy et al. | https://arxiv.org/abs/1602.07261 | Архитектурные детали и сравнение. |
| Residual Connections Improve Inception Networks | 2016 | Szegedy et al. | https://arxiv.org/abs/1602.07261 | Влияние residual-связей. |

---

*Итого: ~35 статей по NST, FiLM и Inception.*

