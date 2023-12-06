# SelfChecker

## File Structure
PAPERS
├── RobOT
│   ├── cifar10
│   │   ├── checkpoint
│   │   ├── cifar10_conv
│   │   ├── cifar10_conv_old
│   │   ├── cifar10_resnet
│   │   ├── cifar10_vgg16
│   │   ├── cifar10_vgg16_old
│   │   ├── pics
│   │   ├── __pycache__
│   │   └── saved_models
│   ├── FASHION
│   │   ├── checkpoint
│   │   ├── fmnist_conv
│   │   ├── fmnist_conv_old
│   │   ├── fmnist_resnet
│   │   └── __pycache__
│   ├── mnist
│   │   ├── checkpoint
│   │   ├── mnist_conv
│   │   ├── mnist_resnet
│   │   ├── mnist_resnet_old
│   │   ├── mnist_vgg16
│   │   ├── mnist_vgg16_old
│   │   └── __pycache__
│   └── SVHN
│       ├── checkpoint
│       ├── data
│       └── __pycache__
├── SelfChecker_Autothreshold
│   ├── models
│   ├── __pycache__
│   └── tmp
│       ├── cifar10
│       │   ├── conv
│       │   │   └── kdes-pack
│       │   ├── resnet
│       │   └── vgg16
│       │       └── kdes-pack
│       ├── fmnist
│       │   ├── conv
│       │   │   └── kdes-pack
│       │   ├── resnet
│       │   └── vgg16
│       └── mnist
│           ├── conv
│           │   └── kdes-pack
│           ├── resnet
│           │   └── kdes-pack
│           └── vgg16
│               └── kdes-pack
├── **SelfChecker_GenAdv**
│   ├── graphs
│   ├── img
│   ├── models
│   ├── *plots_of_result*
│   ├── **main_kde_tf.py**
│   ├── **kde_generation_tf.py** 
│   ├── **prediction_analysis.py**
│   ├── **selection.py**
│   ├── __pycache__
│   └── tmp
│       ├── cifar10
│       │   ├── conv
│       │   │   ├── adv_compare_num
│       │   │   ├── adv_compare_num_10k
│       │   │   ├── adv_compare_num_1k
│       │   │   ├── adv_compare_num_diffpoint_1k
│       │   │   ├── adv_compare_num_old6k
│       │   │   ├── adv_compare_num_unweighted_1k
│       │   │   ├── **adv_compare_num_weighted_1k**
│       │   │   ├── changed_label_pics
│       │   │   └── kdes-pack
│       │   ├── resnet
│       │   │   ├── adv_compare_num
│       │   │   ├── adv_compare_num_10k
│       │   │   ├── adv_compare_num_1k
│       │   │   ├── adv_compare_num_diffpoint_1k
│       │   │   ├── adv_compare_num_old
│       │   │   ├── adv_compare_num_unweighted_1k
│       │   │   ├── **adv_compare_num_weighted_1k**
│       │   │   ├── changed_label_pics
│       │   │   ├── kdes-pack
│       │   │   └── new_method
│       │   └── vgg16
│       │       ├── adv_compare_num
│       │       ├── adv_compare_num_10k
│       │       ├── adv_compare_num_1k
│       │       ├── adv_compare_num_diffpoint_1k
│       │       ├── adv_compare_num_old
│       │       ├── adv_compare_num_unweighted_1k
│       │       ├── **adv_compare_num_weighted_1k**
│       │       ├── changed_label_pics
│       │       ├── kdes-pack
│       │       └── new_method
│       ├── fmnist
│       │   ├── conv
│       │   │   ├── adv_compare_num
│       │   │   ├── adv_compare_num_10k
│       │   │   ├── adv_compare_num_1k
│       │   │   ├── adv_compare_num_diffpoint_1k
│       │   │   ├── adv_compare_num_old
│       │   │   ├── adv_compare_num_unweighted_1k
│       │   │   ├── **adv_compare_num_weighted_1k**
│       │   │   ├── changed_label_pics
│       │   │   ├── kdes-pack
│       │   │   └── new_method
│       │   ├── resnet
│       │   │   ├── adv_compare_num
│       │   │   ├── adv_compare_num_10k
│       │   │   ├── adv_compare_num_1k
│       │   │   ├── adv_compare_num_diffpoint_1k
│       │   │   ├── adv_compare_num_old
│       │   │   ├── adv_compare_num_unweighted_1k
│       │   │   ├── **adv_compare_num_weighted_1k**
│       │   │   ├── changed_label_pics
│       │   │   ├── kdes-pack
│       │   │   └── new_method
│       │   └── vgg16
│       │       ├── adv_compare_num
│       │       ├── adv_compare_num_10k
│       │       ├── adv_compare_num_1k
│       │       ├── adv_compare_num_diffpoint_1k
│       │       ├── adv_compare_num_old
│       │       ├── adv_compare_num_unweighted_1k
│       │       ├── **adv_compare_num_weighted_1k**
│       │       ├── kdes-pack
│       │       └── new_method
│       └── mnist
│           ├── conv
│           │   ├── adv_compare_num
│           │   ├── adv_compare_num_10k
│           │   ├── adv_compare_num_1k
│           │   ├── adv_compare_num_diffpoint_1k
│           │   ├── adv_compare_num_old
│           │   ├── adv_compare_num_unweighted_1k
│           │   ├── **adv_compare_num_weighted_1k**
│           │   ├── changed_label_pics
│           │   ├── kdes-pack
│           │   └── new_method
│           ├── resnet
│           │   ├── adv_compare_num
│           │   ├── adv_compare_num_10k
│           │   ├── adv_compare_num_1k
│           │   ├── adv_compare_num_diffpoint_1k
│           │   ├── adv_compare_num_old
│           │   ├── adv_compare_num_unweighted_1k
│           │   ├── **adv_compare_num_weighted_1k**
│           │   ├── changed_label_pics
│           │   ├── kdes-pack
│           │   └── new_method
│           └── vgg16
│               ├── adv_compare_num
│               ├── adv_compare_num_10k
│               ├── adv_compare_num_1k
│               ├── adv_compare_num_diffpoint_1k
│               ├── adv_compare_num_old
│               ├── adv_compare_num_unweighted_1k
│               ├── **adv_compare_num_weighted_1k**
│               ├── changed_label_pics
│               ├── kdes-pack
│               └── new_method
└── SelfChecker_GenAdv_Backup
    ├── img
    ├── models
    ├── __pycache__
    └── tmp
        ├── cifar10
        │   ├── conv
        │   │   ├── adv_compare_num
        │   │   └── kdes-pack
        │   └── vgg16
        │       ├── adv_compare_num
        │       ├── adv_compare_num_old
        │       └── kdes-pack
        ├── fmnist
        │   └── conv
        │       ├── adv_compare_num
        │       ├── adv_compare_num_old
        │       └── kdes-pack
        └── mnist
            ├── conv
            │   ├── adv_compare_num
            │   └── kdes-pack
            ├── resnet
            │   ├── adv_compare_num
            │   ├── adv_compare_num_old
            │   └── kdes-pack
            └── vgg16
                ├── adv_compare_num
                ├── adv_compare_num_old
                └── kdes-pack

## Directory Information
* RobOT(**No need to modified**): The baseline for comparison. There are four folders named after the dataset it uses. In each folder, there are two `.py` files that are important, named as `fol_guided_fuzzing_5min.py` and `evaluate_fol.py`. 
`fol_guided_fuzzing_5min.py` is used to generate perturbed test cases following ROBOT way. The model used can be modified in the file itself. Usually 5min version generates enough samples for comparison. The generated test cases are stored in the directory {dataset}_{model}, e.g. `cifar10_conv`. The command line is `python fol_guided_fuzzing_5min.py`. The testing file
`evaluate_fol.py` is for evaluating the metrics including robustness improvement and retrained accuracy. The command line is `python evaluate_fol.py`. The result is directly printed in the terminal

* SelfChecker_Autothreshold(**No need to modified**): Used to generate kde functions. For each combination of dataset and model, the command line is `python main_kde.py --d dataset_name --m model_name`. Replace `dataset_name` and `model_name` accordingly. The generated kdes functions are stored in the SelfChecker_GenAdv directory.

* SelfChecker_GenAdv(**main**):This should be the main working directory.

`main_kde_tf.py`: Used to generate perturbed test samples. You can modify the targeted dataset and model, number of samples generated, weights for calculating diff_point and gradient. The command line is `python main_kde_tf.py --d dataset_name --m model_name --gpu number_of_gpu`, e.g. using gpu 3 to calculate cifar10 and ConvNet combination: `python main_kde_tf.py --d cifar10 --m conv --gpu 3`. The number of samples and weigtes need to modify in the file.

`kdes_generation_tf.py`(**important**): The logic of generating perturbed samples. The main logic of calculating entropy is written in function `fetch_kde_tf`. 

`prediction_analysis.py`: Used to analyze the result. Remember to select the correct directory where the perturbed samples are stored by setting the correct datapath of `path_prefix`. The result are printed on the terminal, but also stored in `analysis_result.txt`. A example command line is `python prediction_analysis.py --d cifar10 --m conv --gpu 0`.

`selections.py`:Some selection methods inlucding Entropy, Surprise Adequacy(SA) and LayerEntropy. Used as a library in `prediction_analysis.py`.

`Analysis_result.txt`: history result of `prediction_analysis.py`.

`perturbed_hist.txt`:History of pertubation. Each row is made up by:1) the predicted label by each activation layer 2) the set of total unique labels 3) The true label

`exe.sh`,`rename.sh`,`result_analysis.sh`:Bash files for executing files in paralell.

**below are files not important**

`image_quality.py`: Check the RMSE of perturbed pictures and plot the pictures. e.g. `python image_quality.py --d cifar10 --m conv`

`attack.py`: Code for PGD and FGSM.

`add_layers.py`:This is another approach using multiple sub neural networks instead of kde. The result is not as good as the kde one.


