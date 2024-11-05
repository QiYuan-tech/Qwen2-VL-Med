<img src="./assets/logo.png" class="center-image">

## 📦Model

<!--
|Model Name|Download|Loss|
|:-|:-|:-:|
|Qwen2-VL-7B-Med|[Weights](https://modelscope.cn/models/wangrongsheng/Qwen2-VL-7B-Med) / [Checkponints](https://modelscope.cn/models/wangrongsheng/Qwen2-VL-7B-Med-checkpoints)|![](./assets/loss1.png)|

|🔬Qwen2-VL-7B-Med|0.4453|0.4667|**0.5407**|0.3771|0.3217|0.3032|0.5057|0.3400|0.3926|0.2000|0.6250|0.4979|0.4709|0.4267|**0.5647**|0.2946|0.2609|**0.3054**|**0.3857**|


|🔬Qwen2-VL-7B-Med|0.4521|**0.7200**|0.4500|0.6300|0.4700|0.3300|0.3300|0.5300|0.3700|0.7300|0.7900|0.4000|0.4400|0.4300|0.4300|0.5100|0.5200|0.5600|0.5100|

|🔬Qwen2-VL-7B-Med|0.4453|0.3254|0.4710|0.4388|0.4731|
-->

## 📚Evaluation

> [!NOTE]
> 
> [GMAI-MMBench](https://uni-medical.github.io/GMAI-MMBench.github.io/), represents a pioneering benchmark specifically tailored for the medical domain, aimed at offering thorough assessments of Large Vision-Language Models (LVLMs) in diverse healthcare facets. Constructed from an extensive collection of 284 datasets sourced from both public repositories and hospitals, it encompasses a wide array of medical imaging modalities—38 in total—as well as addresses 18 clinical-related tasks and spans across 18 departments within the healthcare sector. Additionally, the dataset incorporates 4 levels of perceptual granularity, all formatted in a Visual Question Answering (VQA) style to facilitate its use.

#### 📗Clinical Tasks

|Model Name|Overall|Attribute Recognition|Blood Vessels Recognition|Bone|Cell Recognition|Counting|Disease Diagnosis|Image Quality Grading|Microorganism Recognition|Muscle|Nervous Tissue|Organ Recognition - Abdomen|Organ Recognition - Head and Neck|Organ Recognition - Pelvic|Organ Recognition - Thorax|Severity Grading|Surgeon Action Recognition|Surgical Instrument Recognition|Surgical Workflow Recognition|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|Qwen2-VL-7B-Instruct|**0.4646**|**0.5037**|0.4815|0.3829|**0.4261**|0.3085|**0.5386**|**0.3600**|**0.4074**|**0.2600**|0.6250|**0.5224**|**0.5032**|**0.5067**|0.5118|0.2768|**0.3304**|0.2971|0.2857|
|Qwen2-VL-2B-Instruct|0.4305|0.4222|0.4370|**0.4057**|0.4174|**0.3191**|0.5057|0.3000|0.3852|**0.2600**|**0.7250**|0.3388|0.4387|0.4267|0.4647|**0.3155**|0.2870|0.2636|0.2571|
|Qwen-VL-7B-Chat|0.3363|0.2741|0.3704|0.3600|0.3130|0.1011|0.4152|0.2200|0.2593|0.2800|0.4750|0.2571|0.3613|0.2400|0.2588|0.1913|0.1913|0.2343|0.2857|
|HuatuoGPT-Vision-34B|0.5121|0.4889|0.5407|0.5200|0.3652|0.3245|0.5957|0.4200|0.4889|0.2400|0.7250|0.5388|0.6452|0.4933|0.5882|0.3393|0.2609|0.2678|0.4000|
|HuatuoGPT-Vision-7B|0.4890|0.4889|0.5481|0.4686|0.3913|0.2926|0.5825|0.3400|0.4444|0.2800|0.7500|0.4939|0.5484|0.4267|0.5294|0.3006|0.2522|0.2594|0.3714|
|Yi-VL-34B|0.3349|0.3926|0.4000|0.3257|0.3565|0.3085|0.3775|0.2600|0.2815|0.1800|0.4500|0.2408|0.2516|0.2800|0.2471|0.3095|0.2087|0.2971|0.3143|

#### 📙Departments

|Model Name|Overall|Cardiovascular Surgery|Dermatology|Endocrinology|Gastroenterology and Hepatology|General Surgery|Hematology|Infectious Diseases|Laboratory Medicine and Pathology|Nephrology and Hypertension|Neurosurgery|Obstetrics and Gynecology|Oncology (Medical)|Ophthalmology|Orthopedic Surgery|Otolaryngology (ENT)/Head and Neck Surgery|Pulmonary Medicine|Sports Medicine|Urology|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|Qwen2-VL-7B-Instruct|**0.4646**|0.7176|**0.4486**|**0.6400**|**0.4805**|**0.3260**|**0.3428**|**0.5429**|**0.3813**|**0.7467**|**0.8000**|**0.4133**|**0.4524**|**0.4446**|**0.4472**|**0.5231**|**0.5358**|**0.5768**|**0.5222**|
|Qwen2-VL-2B-Instruct|0.4200|0.6800|0.4200|0.6000|0.4400|0.3000|0.3200|0.5000|0.3600|0.7200|0.7600|0.3900|0.4200|0.4100|0.4200|0.5000|0.5100|0.5400|0.5000|
|Qwen-VL-7B-Chat|0.3363|0.6200|0.3800|0.5200|0.3600|0.2800|0.2900|0.4800|0.3000|0.6800|0.7000|0.3500|0.3700|0.3600|0.3500|0.4500|0.4600|0.4900|0.4500|
|HuatuoGPT-Vision-34B|0.5212|0.7500|0.4600|0.6500|0.5000|0.3500|0.3500|0.5500|0.4000|0.7600|0.8200|0.4200|0.4600|0.4500|0.4600|0.5300|0.5400|0.5800|0.5300|
|HuatuoGPT-Vision-7B|0.4890|0.6471|0.4541|0.8400|0.5122|0.3018|0.3493|0.5714|0.4125|0.6800|0.8364|0.4267|0.5187|0.4991|0.5306|0.5077|0.5556|0.6348|0.4389|
|Yi-VL-34B|0.3349|0.6300|0.4000|0.5000|0.4000|0.3000|0.3000|0.5000|0.3500|0.7000|0.7500|0.3800|0.4000|0.4200|0.4000|0.5000|0.5200|0.5500|0.4500|

#### 📘Perceptual Granularities

|Model Name|Overall|Box level|Contour level|Image level|Mask level|
|:-:|:-:|:-:|:-:|:-:|:-:|
|Qwen2-VL-7B-Instruct|**0.4646**|**0.3627**|**0.4815**|**0.4638**|**0.4815**|
|Qwen2-VL-2B-Instruct|0.4305|0.2915|0.4203|0.4401|0.4604|
|Qwen-VL-7B-Chat|0.3363|0.2600|0.3800|0.3500|0.3700|
|HuatuoGPT-Vision-34B|0.5121|0.3700|0.4900|0.4700|0.4900|
|HuatuoGPT-Vision-7B|0.4890|0.3500|0.4850|0.4650|0.4875|
|Yi-VL-34B|0.3349|0.2800|0.4000|0.3600|0.3800|

## 📌Citation

If you find our work helpful, feel free to give us a cite.

```bibtex

```

## 🚩Acknowledgments

## 📬Contact Us

If you are interested in our project and would like to join us, feel free to send an email to [📬wrs6@88.com](mailto:wrs6@88.com).

## 🔔License

Please follow the Apache 2.0 License.
