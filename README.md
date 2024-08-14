<b>Note: Most of the code is private and experiments are still underway.</b>
<br>
<h3 style="font-family: Verdana; font-size: 20px; font-style: normal; font-weight: normal; text-decoration: none; text-transform: none; letter-spacing: 2px; color: teal; background-color: #ffffff;">PROJECT BASIC INFORMATION</h3>

---

<br><b style="text-decoration: underline; font-family: Verdana; text-transform: uppercase;">PRIMARY TASK DESCRIPTION</b>

In this project, we'll create a model to automatically segment the stomach and intestines on MRI scans. The MRI scans are from actual cancer patients who had 1-5 MRI scans on separate days during their radiation treatment. We'll base our algorithm on a dataset of these scans to come up with creative deep learning solutions that will help cancer patients get better care.

<br><b style="text-decoration: underline; font-family: Verdana; text-transform: uppercase;">BASIC BACKGROUND INFORMATION</b>

In 2019, an estimated 5 million people were diagnosed with a cancer of the gastro-intestinal tract worldwide. Of these patients, about half are eligible for radiation therapy, usually delivered over 10-15 minutes a day for 1-6 weeks. Radiation oncologists try to deliver high doses of radiation using X-ray beams pointed to tumors while avoiding the stomach and intestines. With newer technology such as integrated magnetic resonance imaging and linear accelerator systems, also known as MR-Linacs, <b>oncologists are able to visualize the daily position of the tumor and intestines, <mark>which can vary day to day</mark></b>. 

In these scans, radiation oncologists must manually outline the position of the stomach and intestines in order to adjust the direction of the x-ray beams to increase the dose delivery to the tumor and avoid the stomach and intestines. This is a time-consuming and labor intensive process that can prolong treatments from 15 minutes a day to an hour a day, which can be difficult for patients to tolerate—unless deep learning could help automate the segmentation process. <b><mark>A method to segment the stomach and intestines would make treatments much faster and would allow more patients to get more effective treatment.</mark></b>

<br><b style="text-decoration: underline; font-family: Verdana; text-transform: uppercase;">VISUAL EXPLANATION</b>

<center><img src="https://lh5.googleusercontent.com/zbBUgbj1jyZxyu3r1vr5zKKr8yK1hSdwAM3HpD_n6j2W-5-wKP3ZRusi_3yskSgnC-tMRKqOEtLycbLkTWCJAUe4Cylv_VsW81DYI4ray02uZLeSnlzAuZRIU7L2Q0KURYSMqFI"></center><br>

<i>The tumor above (pink thick line) is close to the stomach (red thick line). High doses of radiation are directed to the tumor while avoiding the stomach. Dose levels are represented by colour. Higher doses are represented by red and lower doses are represented by green.</i><br>

<br><center><img src="https://www.humonc.wisc.edu/wp-content/uploads/2017/09/Bayouth_Project4_72ppi.png"></center><br>

<i>MRI is an excellent imaging modality for visualization of soft tissues. This is particularly useful for tumors of the abdomen, such as pancreatic cancer shown below.  The left image shows the patient’s anatomy during exhale, while |the image on the right shows the anatomical change during a maximum inspiration breath hold (MIBH). In the MIBH image we can see motion of nearly all the soft tissue, providing us superior ability to align the tumor during our treatment delivery. We are analyzing the clinical impact of using these treatment planning and delivery techniques and our patient’s ability to comply with self-guided breathing maneuvers.<b><a href="https://www.humonc.wisc.edu/research/medical-physics_research/mr-guided-radiation-therapy-research-2/">[REF]</a></b></i>

<br><b style="text-decoration: underline; font-family: Verdana; text-transform: uppercase;">IMPACT STATEMENT</b>

Cancer takes enough of a toll. If successful, we'll enable radiation oncologists to safely deliver higher doses of radiation to tumors while avoiding the stomach and intestines. This will make cancer patients' daily treatments faster and allow them to get more effective treatment with less side effects and better long-term cancer control.
