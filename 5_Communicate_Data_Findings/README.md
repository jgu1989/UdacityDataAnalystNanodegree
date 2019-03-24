# PISA Data

## Dataset

[PISA](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip&sa=D&ust=1552846825266000) is a survey of students' skills and knowledge as they approach the end of compulsory education. It is not a conventional school test. Rather than examining how well students have learned the school curriculum, it looks at how well prepared they are for life beyond school.

Around 510,000 students in [65 economies](https://www.google.com/url?q=http://www.oecd.org/pisa/aboutpisa/pisa-2012-participants.htm&sa=D&ust=1552846825267000) took part in the PISA 2012 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy.

## Summary of Findings

- Both too few and too many computers at school have negative impact on students' math scores, and similar trend can be observed when the data is resolved by region.
- Gender does not make a big difference in students' math scores.
- Students with the best performance in math are from Shanghai (China), Singapore and Hong Kong (China).
- Generally, students perform better in math if they have more positive attitude towards study.
- The child's performance in math is better when parents both have higher qualifications, but there is an anomaly when parents have the highest qualifications.
- The child performs the best when both father and mother have full-time job, and the worst when neither is working.

## Usage

The full dataset 2.75 GB, and loading it is time consuming. Run pisa.ipynb first so that only the columns of interest will be saved to small csv files. slides.ipynb will then load only these small csv files instead of the full dataset.

To generate slides.slides.html, use the command

```shell
jupyter nbconvert slides.ipynb --to slides --post serve --template output_toggle
```



