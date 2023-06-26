# Basic_shotgun_metagenome
Shotgun Metagenome data handling practise  

# 해당 코드는 Linux(Ubuntu)를 바탕으로 진행됩니다.  

[0. Git bash]  
<details>
<summary>Git bash 활용</summary>
<div markdown="1">       

> Git bash 설치 후,  
> $ git config --global user.name "깃허브이름"  
> $ git config --global user.email "깃허브아이디"  
> $ git clone https://github.com/WoobeenJeong/Basic_shotgun_metagenome.git #깃허브 주소  
> 위 방식으로 작성하면 수정이 용이합니다.

</div>
</details>

[1. 기본 설정]
**대부분의 유전체 분석 Tools은 Window 버전을 지원안하므로, 가상환경 필요**  
예: 
- AWS (Amazon Web service)  
- WLS (Window subsytem for Linux)  
- VirtualBox  
- Docker  

[2. 예시 데이터 출처]  
https://diabimmune.broadinstitute.org/diabimmune/t1d-cohort/resources/metagenomic-sequence-data  
(These data are processed using kneadData v0.4 for quality trimming and human DNA depletion.)

해당 데이터는 위 DIABIMMUNE에서 발췌한 fastq.gz 샘플입니다.  
