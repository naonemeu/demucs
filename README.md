Personal fork for requirements.txt edits and use with the online demucs google colab.

Currently throws a warning, but it mostly works still.

`` 
/usr/local/lib/python3.12/dist-packages/torchaudio/__init__.py:178: UserWarning: The 'encoding' parameter is not fully supported by TorchCodec AudioEncoder.
  return save_with_torchcodec( 
``

``
/usr/local/lib/python3.12/dist-packages/torchaudio/__init__.py:178: UserWarning: The 'bits_per_sample' parameter is not directly supported by TorchCodec AudioEncoder.
  return save_with_torchcodec(
``

Refer to the original repository for the README: https://github.com/adefossez/demucs
