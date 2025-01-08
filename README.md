# BitNet and QAT Analysis

Analysis of BitNet's 1-bit quantization approach and Quantization-Aware Training (QAT) in large language models, comparing BitNet and LLAMA models of 1B and 3B parameters.

## Key Findings

- BitNet weights show significantly larger Frobenius norms compared to LLAMA weights
- Evidence of gradient vanishing in deeper layers, particularly in 3B parameter models
- Quantization loss doesn't strongly correlate with model performance
- QAT achieves comparable accuracy but requires 2x training time

## Analysis Methods

- Weight matrix analysis using Frobenius and spectral norms
- Similarity metrics between pre/post quantization weights
- Performance comparison between BitNet and baseline models
- Training time and resource utilization assessment

## Limitations and Future Work

- Training complexity and time overhead remain significant challenges
- Potential scaling issues due to gradient vanishing
- Future work includes exploring STE modifications and alternative initialization techniques

## Citation

```bibtex
@article{yin2025bitnet,
  title={BitNet and Quantization-Aware Training},
  author={Yin, Aiwei and Bao, Qingyang},
  institution={University of Toronto},
  year={2025}
}
```

## Contributors

- Aiwei Yin
- Qingyang Bao

For questions or feedback, please open an issue in this repository.
