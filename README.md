These codes are supplements to the paper titled "Data-driven predictions of a multiscale Lorenz 96 chaotic system using machine-learning methods: reservoir computing, artificial neural network, and long short-term memory network"
link: https://npg.copernicus.org/articles/27/373/2020/npg-27-373-2020-discussion.html

They contain versions of the Echo State Network, The ANN, and the LSTM. It also contains a data set of the normalized Lorenz96 equations integrated upto 1M time steps.

Alternatively you can use the lorenz solver which is provided as a .m file to integrate the system to as many time steps as you want. This code has been developed by my friend, Adam Subel. 

For any questions, reproducibility issues or concerns about the initial conditons to choose, email me at akc6@rice.edu / ashesh6810@gmail.com

I thank Pantelis, Peter Dueben and Jaideep Pathak for their generousity in sharing or open sourcing codes to perform honest comparisons in this paper. 



Please note that apart from the ESN, which is implemented from scratch the other codes are supported by Keras on a Tensorflow backend. Depending on the Keras version, you may need to change "epochs" to "nb_epoch" or the other way around in the model.fit() API in Keras.

As always, if you use it, please fork it.   


@article{chattopadhyay2020data,
  title={Data-driven predictions of a multiscale Lorenz 96 chaotic system using machine-learning methods: reservoir computing, artificial neural network, and long short-term memory network},
  author={Chattopadhyay, Ashesh and Hassanzadeh, Pedram and Subramanian, Devika},
  journal={Nonlinear Processes in Geophysics},
  volume={27},
  number={3},
  pages={373--389},
  year={2020},
  publisher={Copernicus GmbH}
}
