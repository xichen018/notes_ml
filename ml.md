
MinkowskiDistance(`p-norms)：
dp(x,x0)=||xx0||p =0 @ N X j=1 |xjx0 j|p1 A
1/p
SpecialcasesincludeEuclideandistance(p = 2),Manhattandistance (p = 1)andChebyshevdistance(p =1) 




KNN
- Advantages: 
  - Notrainingperiodisinvolved(i.e.,lazylearning),andnewdata canbeaddedseamlesslywithoutre-trainingthemodel 
  - Convergestothecorrectdecisionsurfaceasdatagoestoinﬁnity 
- Disadvantages: 
  - Doesnotworkwellwithlargedatasets. SinceKNNneedsto storealltrainingdata,performingneighborsearchrequiresalot ofmemoryandtakesalotoftime
  - Doesnotworkwellwithhighdimensions. Itbecomesdifﬁcultfor KNNtocalculatethedistanceineachdimension. Moreover, everythingisfarfromeverythingelseinhighdimensions(the so-called“curseofdimensionality”
  
  
  
  
  # generative models
  
  
Generativeclassiﬁcationmodel 
- Estimateprobabilitydistributionsoffeaturesfromeachclass
- Givenfeature,predictclasswiththelargestposteriorprobability 
- Advantages: 
  - Workswithsmallamountofdata 
  - Workswithmultipleclasses 
- Disadvantages: 
  - Accuracydependsonselectinganappropriateprobability distribution
    - Iftheprobabilitydistributiondoesn’tmodelthedatawell,then accuracymightbebad
