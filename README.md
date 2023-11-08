# OpinionConv: Conversational Product Search with Grounded Opinions

When searching for products, the subjective experiences of others can be a valuable source of information. This is also true in conversational product search, where a customer and a sales assistant exchange facts and opinions about products. However, training an AI for such conversations is complicated by the fact that language models do not possess authentic opinions because of the lack of real-world experience.

With OpinionConv, we develop the first conversational system to simulate sales conversations by leveraging product reviews to ground conversational AI in true subjective narratives.

<p align="center">
  <img src="https://github.com/caisa-lab/OpinionConv/blob/main/src-ipynb/High-level%20Overview%20of%20OpinionConv.png">
</p>

The above figure depicts the high-level overview of our approach in OpinionConv for generating opinionated multi-turn conversations.

OpinionConv enables researchers to study a number of tasks related to conversational product search, including opinionated conversation modeling and opinionated response generation and selection. For more information, refer to the following paper:

- Vahid Sadiri Javadi, Martin Potthast, Lucie Flek.[**"OpinionConv: Conversational Product Search with Grounded Opinions"**](https://arxiv.org/abs/2308.04226), In Proceedings of the 24th Meeting of the Special Interest Group on Discourse and Dialogue, 2023 (SIGDIAL '23).

## Data Generation:

The code in ``src-ipynb/Script.ipynb`` contains the steps that should be followed and executed in a sequential manner to generate the conversational dataset.

**Note**: 

- You need to download the Metadata, Product reviews, and Rating data from the  [**Amazon Review Data (2018)**](https://cseweb.ucsd.edu/~jmcauley/datasets/amazon_v2/)
- The full conversational data can't fit in the zip file. Instead, we provided a data sample in ``ConversationalDataset_Sample.zip`` folder.
- All the GitHub repositories for the pre-trained models that we used in our paper have been listed and explained in the Jupyter Notebook file.


## Citation
If you found our work useful, the paper and the dataset can be cited as follows:

```
@article{javadi2023opinionconv,
  title={OpinionConv: Conversational Product Search with Grounded Opinions},
  author={Javadi, Vahid Sadiri and Potthast, Martin and Flek, Lucie},
  journal={arXiv preprint arXiv:2308.04226},
  year={2023}
}
```
