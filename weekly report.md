##                                ParrotAilPT-2018:WEEKLY REPORT
## WEEK1 REPORT
On the first week of this ParrotAilPT-2018 ,I learn a lot of things that can help me to understand machine 
learning  by using python language.On week one i learning the following key concept: </br>                                                     
        </br>   1.Introduction to Machine Learning </br>                                                                                                 
On this i try to understand what machine learning deals with ,how i can use machine learning to solve  
problem and I try to know how machine learning can extract knowledge from a data.And i achieve this through 
learning different books that concern machine learning concept such as Introduction to machine learning book
Hands on book.     </br>                                                                                                                               
          </br> 2.Main categories of Machine learning </br>                                                                                                  
There are two main categories which are supervised and unsupervised machine learning but on that week 
i was learned about supervised machine learning algorithms which are: </br>                                                                          
               1.linear model                                                                                                                               
               2.K-Nearest Neighbor                                                                                                         
               3.Random Forest                                                                                                                
               4.Decision Tree                                                                                                                   
               5.Naive Bayes                                                                                                                     
               6.Support Vector Machine   </br>                                                                                                       
On this algorithms i learned how i can use cross-validation to minimize overfitting and also i was learned 
before you fit the model you must check you dataset if there is any missing data and to clean that dataset.

Something i noted on my mind in order to perform this algorithm you must know essential library such as 
pandas for data analysis and visulization, and matplotlib,sklearn,numpy.

Also i learn how to analysis data,fix missing value,feature selection and conversion of categorical,ordinal 
data into numerical data.                                                                                                                   
Challenge i face on learning this language for me i need alot of time to build python concept becauthis is new language to me.

Generally:This IPT is best in CIVE and through weekly challenge for my part i can know many things that
concern this language and that can help me to be competence.
  
           

# WEEK2 REPORT
On this week i learn fundamental concept of deep learning which includes the following aspects:
                                </br>    1.Introduction </br>                                                                 
 On this i understand the difference between machine learning and deep learning, why we use deep learning rather than machine learning to solve different problem that surround our environment. And also i learn how deep learning works and how i can use activation function to transform linear function to non-linearity.And i was achieve this through reading book  and sambaiga notes on gitlab ParrotAilPT-2018 group that concern deep learning concept.                                                                                                                                                                                                                               
                                   </br>   2.Training deep neural network </br>
  On this i understand how to train deep neural network and which things i can consider to minimize loss function in both binary and multiclass classification and which activation function i can use on both binary and multiclass classification. In binary will define loss function by(Binary Cross Entropy) and multiclass(cross entropy loss) .Also i compute gradient by using(Backpropagation) and to solve optimization problem that can help me to optimize my model and how i can use momentum to accelerate SGD optimizer to attain global minima.
 Generally on this DDN we deals on three step for formulating ML problem which are:  
                                    1.Hypothesis                                                                                                                                                                                                                       
                                    2.loss function                                                                                              
                                    3.Optimization                                                                                                                                                                                                                                      
                          </br>   3.Deep learning techniques </br>
On this i learn two technique that help you to improve performance and stability of deep learning network which are:
                                  </br>1.Regularization
                                 </br> 2.Batch-Normalization                                                                                                                                                                                                                           
                                  </br> 4.Deep learning architecture</br>
 On this i understand how convolution neural network and recurrent neural network architecture are differ and how it work and why RNN is suitable for long item dimension and sequence data rather than CNN.The following are explanation of that architecture:
                                    </br>  Convolution neural network</br>
CNN implementation on this we use pytorch to build convolution neural network procedure to follow when you build CNN by using pytorch:  
                     </br> 1.You must import all necessary libraries and modules that you want to use.
                     </br> 2.Load train and test datasets by using (dataloader and tensordatasets) or numpy module(loadtxt)
                        for handling data then the output of this we transform to tensor.
                     </br> 3.When you use numpy module to load data you must convert them into tensor by using from_numpy  
                        modules.
                     </br> 4.We make our data loader into batch by setting batch_size and to be iteratable.
                     </br> 5.we define our CNN model here we use conversation layer with maxpool for reduce number of neuron
                        and also we use activation function for conversation into non-linearity note we don't apply
                        activation function on output layer.
                     </br> 6.We define loss function and optimizer function
                     </br> 7.We train network for this we do forward pass computation with mini-batch
                      then clear gradient with respect to parameter  backward pass and  to compute gradient
                      followed by updating step.
                     </br> 8.we test the network on the test data and visualize our data.                                                                                                                                                                                                
                                      </br> 5.Sequence modelling </br>
On this i understand the requirement for model sequence which are:      
                         </br> 1.It deals with variable-length sequence and maintain sequence.
                          </br>2.Keep track of long-term dependencies.
                         </br> 3.It allow to share parameters across the sequence.                                                                  
Something i noted about RNN is the family of sequence modelling because it contain all information about past sequence.
Sequence modelling also include back propagation over each time.                                                                                                                                                                                                                        
                                     </br>  Back propagation through time</br>
On this i understand how back propagation can solving vanishing and exploding gradient problem and how to address them.
                           Vanishing gradient problem are address by using:
			       </br>1.Long short-term memory(LSTM)
                             </br> 2.Gated recurrent unit(GRU) </br>                                                                                                                                                                                                                                                            
Challenge i face on this it need a lot of mathematical concept and to understand basics hint of pytorch in order to be competence.                                                                                                                                                                 
Generally: Through deep learning we able to develope system that can help society to solve different problem.
     



## WEEK3 REPORT

  On this week i learn how to predict user's interest and to simplify search of common recommended item's that user's are likely interest with, we can achieve this by using recommender system and also on this week i review about imbalance concept.                  Recommender can help companies to gain competitive advantage to the competitors. In recommender system i understand the following concept:                                                                                                                                                                                                                                                                             </br>1.  Why recommender system were used in different companies?                                                                  
           2. Advantage of implementing recommender system.                                                                                     
           3. Which type i can use to implementing recommender system and why i use it?                                                          
           4. Things to consider before i building a recommender system.                                                                   
           5. Challenge that facing  recommender system.                                                                                         
           6. how evaluation of recommender system.
  
							  
   Recommender system are divided into two types which show relationship between companies and their user's,the below are the types of recommender:                                                                                                                                                                                                     
         </br>  1. Characteristic information                                                                                                          
This deals with information of user's and item's.  </br>                                                                            
Example: Content-based system which make recommendation using user's profile and item features.</br>                                    
In this we assume that the user's interest of the past can be future interest.  </br>                                                                                                                                                                                                     </br>2. User-item interactions                                                                                                                                                                                         
 This deals with information such as sales, which product needed more by user.</br>
 Example:Collaborative filters in this we assume that interest of one user's also can be interest of other's. </br>                                 
 To minimize the challenge of recommender types we can use hybrid system which combine all type of recommender.</br>
                                                                                                                                      collaborative filters achieve this goals by using two method which are memory-based,model-based</br>
                
  Also in this week i learn how evaluation in recommender system can  be done by using the following method which are  online and offline.</br>                                                                                                                                     
  Also on this week i learn about imbalance which used to decrease or increase majority and minority of classes,the following are techniques used re-sampling and cost-sensitive techniques.On this imbalance concept i deals with re-sampling techniques only  which consist of two methods over-sampling and under-sampling,below are explanation about this methods.</br>

</br>  1.Over-sampling                                                                                                                             
This can increase number of minority to attain majority equilibrium.                                                                                 
Example:SMOTE                

 </br> 2.Under-sampling                                                                                                                      
This can reduce the number of majority to attain minority equilibrium.                                                                           
Example: NearMiss.</br>

On this week we review week one challenge and we implement sampling concept for imbalance class (over-sampling) and also we learn how to arrange you work in good manner.                                                                                                          
Also on this we learn about confusion matrix how it can help you to choice the best model for you challange and also we were saw the different between uses of sampling and without sampling on model.

Generally the implementation of imbalance to dataset it can help to reduce the fairness decision  based on large number of certain class and also recommendation it help companies to increase the productive of item's.</br>




##                                                         WEEK4 REPORT

  Hi,on this week i learn intoduction to competition,how to win kaggle competition and which element can led me to win  competition.
  Competition having the following essential element to consider which are data,model,submission,evaluation </br> and leaderboard.

   Also in kaggle competion tutorial i learn about explanatory data analysis which can help me to understand data and to generate 
  hypothesis.Win kaggle tutorial it cover a lot of things that was already taught by sir!SAMBAIGA include deep explanation about 
  different model and how to implement them.<br>     
    On this week,we work on project as team and we try to build the strong model and set conducive interface that can help </br> bank 
  on provision of loan to customers in order to avoid risk.On this we achieve 50% (percent) of our project work and </br>also on this 
  we try to use sampling concept to our problem in order to increase number of minority to attain equilibrium </br>level of majority.</br>       
     On this week also we discuss strategies for structuring machine learning project in this we discuss different 
   concept that</br>help to improve performance in our model,also we learn about evaluation metric and data,and what is the effect of </br>single metric in performance. </br>             
     Also we learn how to quantify human level performance work on bias and variance gap,bias is the gap between human </br> and training 
   performance while variance is the gap between training  and dev performance. </br>    
       Generally:On this week i learn a lot of things and i solve different problems practically,this week is awesome to me. 	
  </br>Special thanks to sir!Sambaiga who use a lot of time to spread knowledge and i real appeciate you help.
    	 
   
   
   
  
     
   
