# csci567-program-2-neural-networks-solved
**TO GET THIS SOLUTION VISIT:** [CSCI567 Program 2-Neural Networks Solved](https://www.ankitcodinghub.com/product/csci567-program-2-neural-networks-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96568&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI567 Program 2-Neural Networks Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Before You start

On Vocareum, when you submit your homework, it takes around 5-6 minutes to run the grading scripts and evaluate your code. So, please be patient regarding the same.

Problem 1 Neural Networks

For this Assignment, you are asked to implement neural networks. We will be using this neural network to classify MNIST database of handwritten digits (0-9). The architecture of the multi-layer perceptron (MLP, just another term for fully connected feedforward networks we discussed in the lecture) you will be implementing is shown in figure 1. Following MLP is designed for a K-class classification problem.

Let (𝑥 ∈ R𝐷, 𝑦 ∈ {1, 2, ⋯ , 𝐾}) be a labeled instance, such an MLP performs the following computations.

</div>
</div>
<div class="layoutArea">
<div class="column">
𝐢𝐧𝐩𝐮𝐭 𝐟𝐞𝐚𝐭𝐮𝐫𝐞𝐬 : 𝐥𝐢𝐧𝐞𝐚𝐫(1) :

𝐭𝐚𝐧𝐡 : 𝐫𝐞𝐥𝐮 :

𝐥𝐢𝐧𝐞𝐚𝐫(2) :

denote the cross-entropy loss with respect to the training example (𝑥, 𝑦) by 𝑙 : 𝑙=−log(𝑧𝑦)=log 1+𝑘≠𝑦𝑒𝑘 𝑦

</div>
</div>
<div class="layoutArea">
<div class="column">
𝐬𝐨𝐟𝐭𝐦𝐚𝐱 : 𝐩𝐫𝐞𝐝𝐢𝐜𝐭𝐞𝐝 𝐥𝐚𝐛𝐞𝐥 :

</div>
<div class="column">
𝑧= ⎢⋮⎥ ⎢⎥

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑥 ∈ R𝐷

𝑢=𝑊(1)𝑥+𝑏(1) ,𝑊(1) ∈R𝑀×𝐷and𝑏(1) ∈R𝑀

h=2−1

1 + 𝑒−2𝑢 ⎡ max{0, 𝑢 } ⎤

</div>
</div>
<div class="layoutArea">
<div class="column">
⎢1⎥ h = 𝑚𝑎𝑥{0, 𝑢} = ⎢ ⎥

</div>
</div>
<div class="layoutArea">
<div class="column">
⎢⋮⎥ ⎣max{0,𝑢𝑀}⎦

,𝑊(2) ∈R𝐾×𝑀 and𝑏(2) ∈R𝐾

𝑦̂ = 𝑎𝑟𝑔𝑚𝑎𝑥𝑘 𝑧𝑘 .

For a 𝐾 -class classification problem, one popular loss function for training (i.e., to learn 𝑊 (1) , 𝑊 (2) , 𝑏(1) , 𝑏(2) ) is the cross-entropy loss.Specifically we

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑎=𝑊(2)h+𝑏(2)

</div>
</div>
<div class="layoutArea">
<div class="column">
⎡𝑎⎤ ⎢𝑒1⎥

</div>
</div>
<div class="layoutArea">
<div class="column">
⎢𝑎⎥ ⎢ ∑𝑘 𝑒 𝑘 ⎥

</div>
</div>
<div class="layoutArea">
<div class="column">
⎢𝑎⎥ ⎢𝑒𝐾⎥ ⎣∑𝑘𝑒𝑎𝑘 ⎦

</div>
</div>
<div class="layoutArea">
<div class="column">
( ∑𝑎−𝑎)

Note that one should look at 𝑙 as a function of the parameters of the network, that is, 𝑊 (1) , 𝑏(1) , 𝑊 (2) and 𝑏(2) . For ease of notation, let us define the one-hot

</div>
</div>
<div class="layoutArea">
<div class="column">
(i.e., 1-of-𝐾 ) encoding of a class 𝑦 as so that

</div>
<div class="column">
𝑦∈R𝐾 and𝑦𝑘 ={1, if𝑦=𝑘, 0, otherwise.

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑙=−∑𝑦 log𝑧 =−𝑦𝑇 ⎢ ⎥=−𝑦𝑇 log𝑧. 𝑘𝑘⎢⋮⎥

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑘 ⎣log𝑧𝐾 ⎦

We can then perform error-backpropagation, a way to compute partial derivatives (or gradients) w.r.t the parameters of a neural network, and use gradient-

</div>
</div>
<div class="layoutArea">
<div class="column">
based optimization to learn the parameters.

Submission: All you need to submit is neural_networks.py.

Q1.1 Mini batch Gradient Descent

First, you need to implement mini-batch gradient descent which is a gradient-based optimization to learn the parameters of the neural network. You need to realize two alternatives for SGD, one without momentum and one with momentum. We will pass a variable 𝛼 to indicate which option. When 𝛼 ≤ 0, the parameters are updated just by gradient. When 𝛼 &gt; 0, the parameters are updated with momentum.

𝜐 = 𝛼𝜐−𝜂𝛿𝑡

𝑤𝑡 = 𝑤𝑡−1 + 𝜐 You can use the formula above to update the weights using momentum.

Here, 𝛼 is the discount factor such that 𝛼 ∈ (0, 1)

𝜐 is the velocity update 𝜂 is the learning rate

𝛿𝑡 is the gradient

You need to handle with as well without momentum scenario in the miniBatchGradientDescent function.

TODO 1 You need to complete def miniBatchGradientDescent(model, momentum, _lambda, _alpha, _learning_rate) in

<pre>    neural_networks.py
</pre>
Q1.2 Linear Layer (10 Points)

Second, You need to implement the linear layer of MLP. In this part, you need to implement 3 python functions in class linear_layer . In def __init__(self, input_D, output_D) function, you need to initialize W with random values using np.random.normal such that the mean is 0 and standard deviation is 0.1. You also need to initialize gradients to zeroes in the same function

(1) (1) (1) 𝐟𝐨𝐫𝐰𝐚𝐫𝐝 𝐩𝐚𝐬𝐬: 𝑢 = linear .forward(𝑥) = 𝑊 𝑥 + 𝑏 ,

</div>
</div>
<div class="layoutArea">
<div class="column">
⎡log𝑧 ⎤ ⎢1⎥

</div>
</div>
<div class="layoutArea">
<div class="column">
where 𝑊 (1) and 𝑏(1) are its parameters. ∂𝑙∂𝑙∂𝑙(1) ∂𝑙

</div>
</div>
<div class="layoutArea">
<div class="column">
𝐛𝐚𝐜𝐤𝐰𝐚𝐫𝐝 𝐩𝐚𝐬𝐬: [ ∂𝑥 , ∂𝑊 (1) , ∂𝑏(1) ] = linear .backward(𝑥, ∂𝑢 ).

</div>
</div>
<div class="layoutArea">
<div class="column">
In [ ]:

</div>
</div>
<div class="layoutArea">
<div class="column">
You can use the above formula as a reference to implement the def forward(self, X) forward pass and def backward(self, X, grad) backward pass in class linear_layer . In backward pass, you only need to return the backward_output. You also need to compute gradients of W and b in backward pass

TODO 2 You need to complete def __init__(self, input_D, output_D) in class linear_layer of neural_networks.py TODO 3 You need to complete def forward(self, X) in class linear_layer of neural_networks.py

TODO 4 You need to complete def backward(self, X, grad) in class linear_layer of neural_networks.py

Activation Function-tanh(10 Points)

Now, you need to implement the activation function tanh. In this part, you need to implement 2 python functions in class tanh . In def forward(self, X) , you need to implement the forward pass and you need to compute the derivative and accordingly implement def backward(self, X, grad) , i.e. the backward pass.

𝐭𝐚𝐧𝐡 : h = 2 − 1 1 + 𝑒−2𝑢

You can use the above formula for tanh as a reference.

TODO 5 You need to complete def forward(self, X) in class tanh of neural_networks.py

TODO 6 You need to complete def backward(self, X, grad) in class tanh of neural_networks.py

Activation Function-relu(10 Points)

You need to implement another activation function called relu. In this part, you need to implement 2 python functions in class relu . In def forward(self, X) , you need to implement the forward pass and you need to compute the derivative and accordingly implement def backward(self, X, grad) , i.e. the backward pass.

</div>
</div>
<div class="layoutArea">
<div class="column">
𝐫𝐞𝐥𝐮 :

TODO 7 You need to complete def forward(self, X) in class relu of neural_networks.py

</div>
</div>
<div class="layoutArea">
<div class="column">
h = 𝑚𝑎𝑥{0, 𝑢} = ⎢ ⎥ ⎢⋮⎥

</div>
</div>
<div class="layoutArea">
<div class="column">
⎣max{0,𝑢𝑀}⎦

TODO 8 You need to complete def backward(self, X, grad) in class relu of neural_networks.py

Q1.5 Dropout(10 Points)

To prevent overfitting, we usually add regularization. Dropout is another way of handling overfitting. In this part, you will initially read and understand def forward(self, X, is_train) i.e. the forward pass of class dropout and derive partial derivatives accordingly to implement def backward(self, X, grad) i.e. the backward pass of class dropout . We define the forward and the backward passes as follows.

forward pass:

backward pass:

Note that 𝑝𝑗, 𝑗 ∈ {1, ⋯ , 𝐽} and 𝑟 are not be learned so we do not need to compute the derivatives w.r.t. to them. Moreover, 𝑝𝑗, 𝑗 ∈ {1, ⋯ , 𝐽} are re-

sampled every forward pass, and are kept for the following backward pass. The dropout rate 𝑟 is set to 0 during testing.

TODO 9 You need to complete def backward(self, X, grad) in class dropout of neural_networks.py

Q1.6 Connecting the Dots

In this part, you will combine the modules written from question Q1.1 to Q1.5 by implementing TODO snippets in the def main(main_params, optimization_type=”minibatch_sgd”) i.e. main function. After implementing forward and backward passes of MLP layers in Q1.1 to Q1.5,now in the main function you will call the forward methods and backward methods of every layer in the model in an appropriate order based on the architecture.

TODO 10 You need to complete main(main_params, optimization_type=”minibatch_sgd”) in neural_networks.py

Grading

Your code will be graded on Vocareum with autograding script. For your reference, the solution code takes around 5 minutes to execute. As long as your code can finish grading on Vocareum, you should be good. When you finish all TODO parts, please click submit button on Vocareum. Sometimes you may need to come back to check grading report later.

Your code will be tested on the correctness of modules you have implemented as well as certain custom testcases. 40 points are assigned for Question 1 while 60 points are assigned to custom testcases.

Grading Guideline for Neural Networks (100 points) Question 1

1. Linear Layer: 10 points

2. Activation Function-tanh: 10 points 3. Activation Function-relu: 10 points 4. Dropout:10 points

Question 2

1. Custom testcases: 60 points

2. Make sure to complete the miniBatchGradientDescent and main functions for the custom cases to run. You will not receive any points for the custom test

</div>
</div>
<div class="layoutArea">
<div class="column">
You can use the above formula for relu as a reference.

</div>
</div>
<div class="layoutArea">
<div class="column">
⎡ max{0,𝑢 } ⎤ ⎢1⎥

</div>
</div>
<div class="layoutArea">
<div class="column">
cases if these functions are not complete.

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑠 = dropout.forward(𝑞 ∈ R𝐽 ) = × ⎢ ⎥ 1−𝑟⎢⋮⎥

</div>
<div class="column">
,

</div>
</div>
<div class="layoutArea">
<div class="column">
⎣1[𝑝𝐽 &gt;=𝑟]×𝑞𝐽⎦ where 𝑝𝑗 is sampled uniformly from [0, 1), ∀𝑗 ∈ {1, ⋯ , 𝐽},

</div>
</div>
<div class="layoutArea">
<div class="column">
and 𝑟 ∈ [0, 1) is a pre-defined scalar named dropout rate. ⎡⎤

</div>
</div>
<div class="layoutArea">
<div class="column">
∂𝑙 = dropout.backward(𝑞, ∂𝑙 ) = 1 × ⎢ ⋮

⎢ ∂𝑙 ⎥

</div>
</div>
<div class="layoutArea">
<div class="column">
⎥ . ∂𝑞 ∂𝑠1−𝑟⎢ ⎥

</div>
</div>
<div class="layoutArea">
<div class="column">
⎡1[𝑝 &gt;=𝑟]×𝑞 ⎤ 1⎢11⎥

</div>
</div>
<div class="layoutArea">
<div class="column">
⎢1[𝑝 &gt;=𝑟]× ∂𝑙 ⎥ ⎢1 ∂𝑠⎥

</div>
</div>
<div class="layoutArea">
<div class="column">
⎢1⎥

</div>
</div>
<div class="layoutArea">
<div class="column">
⎢1[𝑝 &gt;=𝑟]× ⎥ ⎣𝐽 ∂𝑠𝐽⎦

</div>
</div>
</div>
</div>
