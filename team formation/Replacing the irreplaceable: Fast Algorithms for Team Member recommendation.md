## Replacing the Irreplaceable: Fast Algorithms for Team Member Recommendation

- **Conference**
    - WWW 2015
- **Author**
    - Liangyue Li
        - Arizona State University
    - Hanghang Tong
        - Arizona State University
    - Nan Cao
        - IBM Research
    - Kate Ehrlich
        - IBM Research
    - Yu-Ru Lin
        - University of Pittsburgh
    - Norbou Buchler
        - US Army Research Laboratory

- **Note**
    - **Problem statement:** 當團隊中有member要離開團對時，該如何從剩下的人選中挑出一個來取代,ex:籃球受傷換人
    - **key point:** 選出候選人來取代已存在的團員，為了能使團隊達到synergy（skill matching and structure matching），因為替代的人不只要skill相近，待與團隊的化學作用也要提升或者不下降太多，很多成功是來自小的任務的成功，替代與被替代越相似越好
    - **Method**
    - skill, structure , interaction
    - compare 取代前和取代後的sub-graphs 在總合起來當做similarity依據
    - use graph kernel(random walk based)


- **Dataset**：
    - DBLP
    - IMDb
    - NBA

- **Other reference**
    - [source code](http://www.public.asu.edu/~liangyue/teamrep.html)


