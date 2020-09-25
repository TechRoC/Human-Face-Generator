# Human-Face-Generator
The idea behind this project is to start from random noise and to apply DCGAN to generate real-like human Faces that don't
even exist.

## *importing libraries*

{
      "cell_type": "code",
      "metadata": {
        "id": "8nmQATYKy0dS",
        "colab_type": "code",
        "colab": {}
      },
      "source": [
        "from __future__ import absolute_import\n",
        "from __future__ import division\n",
        "from __future__ import print_function\n",
        "\n",
        "from tensorflow.keras.layers import Activation, Dense, Input\n",
        "from tensorflow.keras.layers import Conv2D, Flatten\n",
        "from tensorflow.keras.layers import Reshape, Conv2DTranspose\n",
        "from tensorflow.keras.layers import LeakyReLU,Dropout\n",
        "from tensorflow.keras.layers import BatchNormalization\n",
        "from tensorflow.keras.optimizers import RMSprop\n",
        "from tensorflow.keras.models import Model\n",
        "from tensorflow.keras.datasets import mnist\n",
        "from tensorflow.keras.models import load_model\n",
        "from tensorflow.keras.layers import * \n",
        "import numpy as np\n",
        "import math\n",
        "import matplotlib.pyplot as plt\n",
        "import os\n",
        "import argparse\n",
        "import time\n",
        "from tensorflow.keras import backend as K\n"
      ],
      "execution_count": null,
      "outputs": []
    }

# Dataset
https://www.kaggle.com/jessicali9530/celeba-dataset


# Result
![Fake_Faces](https://user-images.githubusercontent.com/60687531/92041095-3bf45600-ed95-11ea-99f9-6fffd78579ce.gif)
