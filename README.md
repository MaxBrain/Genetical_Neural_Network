# Genetical_Neural_Network
Genetical Neural Network is a Defold example project on how to create a simple Neural Network with genetical renforcement (which means it learn by himself by selecting the best specimen of each generation and reproduce it with some mutation in the next generation). The project is fully commented for an easier understanding of how it work. The project consist on a race delimited by walls, every generation 10 cars spawn with each of them their own neural network, after 10sec the next car's generation spawn, with a neural network based on the best of the previous generation but with random mutation. The purpose for the cars is to finish the race the faster possible without  hitting any wall. The best car's neural network is saved  here : C:\Users\ UserName \AppData\Roaming\AI_test.
Keep in mind while creating your own race that the neural network have no way to know where the finish.go is,
all he do his following the wall and try not to touch them. Also if you want a better undertsanding of this
neural network, go to : https://forum.defold.com/t/articifial-neural-network-ai/27667.
