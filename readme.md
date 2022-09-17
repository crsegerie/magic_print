## Usage

Print the type contained in complex nested python structures recursively.

## Install

!pip install magic-print==0.1.0

## Example

from magic_print.magic_print import print_magically
print_magically(nested_object) # could be a dict, tuple, nested dict, torch tensor...


>>>

 <class 'transformers.generation_utils.SampleDecoderOnlyOutput'>
  sequences Tensor of shape: torch.Size([3, 20])
  scores <class 'tuple'>
    0 Tensor of shape: torch.Size([3, 50257])
    1 Tensor of shape: torch.Size([3, 50257])
    2 Tensor of shape: torch.Size([3, 50257])
    3 Tensor of shape: torch.Size([3, 50257])

