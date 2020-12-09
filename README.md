# kurtag_kafka-fragments
data sets for performance analyses of György Kurtág’s *Kafka-Fragmente* (1985–87) for Soprano and Violin.

This repository introduces the data sets created during research on recorded performances of György Kurtág’s *Kafka-Fragmente* (1985–87). It complements the following three articles:

Utz, Christian (2020). “Kontinua aus Diskontinuitäten. Dimensionen der performativen Form in Interpretationen von György Kurtágs *Kafka-Fragmenten*.” In *György Kurtág* (Musik-Konzepte Sonderband), ed. by Ulrich Tadday. Munich: edition text + kritik, 215–258. 

Motavasseli, Majid (2020). “‘Ein Kaleidoskop im klassischen Rahmen.’ Zum Zyklusproblem in György Kurtágs *Kafka-Fragmenten*.” In *György Kurtág* (Musik-Konzepte Sonderband), ed. by Ulrich Tadday. Munich: edition text + kritik, 259–282. 

Glaser, Thomas (2020). “‘(…) aus mehr oder weniger zerklüfteten Bruchstücken große, weitläufige musikalische Formgebilde (…) bauen.’ Klanglich-aufführungspraktische Gestaltung makroformaler Zusammenhänge in Tonaufnahmen von György Kurtágs *Kafka-Fragmenten* für Sopran und Violine op. 24.” In *György Kurtág* (Musik-Konzepte Sonderband), ed. by Ulrich Tadday. Munich: edition text + kritik, 283–304. 

**main content** [in progress]

The data are presented here as **one [Excel file](Kurtag_Kafka-Fragmente_total_data.xlsx)** that includes data referring to the whole cycle and **40 further Excel files** (Kurtag_Kafka-Fragmente_**xx**_data.xlsx) that include data referring to the 40 individual movements of Kurtág’s cycle. The most important data for the whole cycle and for each movement are also provided as **tsv**-files separately. The duration data refer to sections and segments indicated in an annotated score of this work that has been published in open access at https://phaidra.kug.ac.at/o:107318.

**data content**

--Kurtag_Kafka-Fragmente_discography.xlsx (also available as .tsv): a complete discography of the published and unpublished recordings of Kurtág’s *Kafka-Fragmente* that were analyzed.

--Kurtag_Kafka-Fragmente_total_data.xlsx: This Excel file contains **4 worksheets** of data covering the entire cycle of 40 movements. 
* 'KF-dur_raw data' presents the raw duration data of all 40 movements in 14 recordings in seconds with colored scaling of values (green=low, yellow=mid, red=high) for each movement. Maximum, minimum, and mean values as well as relative standard deviation and relative range (maximum and miniumum values relative to the mean) are provided on the basis of all **14 recordings** and a subgroup of **8 recordings** in which every performer is represented only once (with the exception of András Keller who recorded the work with two different sopranos).
* 'KF-dur+perc 14' presents the same duration values and statistical values of all 14 recordings with durations rendered in a min:sec format; it also identifies those recordings that have the minimum and maximum duration in each movement; the percentage of the toal duration is provided for each movement along with max, min, mean, absolute standard deviation, and absolute range values. Durations and percentages are also presented for the four main parts of the cycle (I, II, III, IV, containing movements 1–19, 20, 21–32, 33–40). In addition, the relative deviation of each movement’s duration from the mean and the absolute deviation of each percentage value from the mean are provided.
* 'KF-dur+perc 8' presents the same set of data as 'KF-dur+perc 14' for the subgroup of 8 recordings.
* 'KF-dur-dev 8' collects a number of additional absolute and relative deviation tables for the subgroup of 8 recordings.

--Kurtag_Kafka-Fragmente_total_data_basic-14.tsv: presents the basic data of worksheet 'KF-dur+perc 14' in tsv-format.

--Kurtag_Kafka-Fragmente_total_data_basic-8.tsv: presents the basic data of worksheet 'KF-dur+perc 8' in tsv-format.

--'fragments_1-40_data' subfolder: This folder contains 40 Excel files, one for each movement. Each file contains **10 basic worksheets** with **additional 3 worksheets** contained for movements 1, 8, 9, 13 und 17 that document tempo values based on the basic beat unit (beats per minute bpm). The worksheet 'score' calculates the percentages of segments and sections based on note values in the score. The main worksheet 'KF_xx_dur+rat' presents detailed data on the duration, percentages, deviations, and other statistical values for sections and segments of the respective movement. The data are summarized in 8 tables at the left bottom of the sheet where durations and percentages of both sections and segments are represented for both the 14- and the 8-recording corpora.

--'fragments_1-40_basic-data' subfolder: This folder contains 40 tsv-files that contain the 8 tables of basic data from the worksheet 'KF_xx_dur+rat' in the respective Excel files.

**glossary**

dur: duration/durations<br>
perc: percentage/percentages (of total duration)<br> 
mean: mean (average) value<br>
max: maximum value<br>
min: miniumum value<br>
abs stdv: absolute standard deviation<br>
rel stdv (%): relative standard deviation (%)<br>
rel range + (%): relative range + (%) – percentage of maximum value in relation to mean value<br>
rel range - (%): relative range - (%) – percentage of minimum value in relation to mean value<br>
rel range (%): relative range (%) – range between minimum and maximum value as percentage of mean value<br>
score: percentages of sections and segments have been calculated on the basis of the note values provided in the score incorporating fermatas<br>
dev: (absolute) deviation<br>
rel dev (%): relative deviation (%)<br>
min: minute(s)<br>
sec: second(s)<br>
part(s) (A, B, A'): formal units expressed with regard to similarity and difference/contrast of musical content<br>
sec: section(s) (1, 2, 3…): larger form-dividing units<br>
seg: segment(s) (1a, 1b, 1c): smaller form-dividing units<br>

