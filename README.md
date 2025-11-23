Personal fork for requirements.txt edits and use with the online demucs google colab.

### Extra instructions 
In your google colab docs, replace the isntall link with this one.

After installing demucs, but before running it, place a code block to install torchcodec.

```!pip install tochcodec```

### Remaining Issues
Currently throws a warning, but it mostly works still. (16/24 bit option being ignored?)

```
/usr/local/lib/python3.12/dist-packages/torchaudio/__init__.py:178:
UserWarning: The 'encoding' parameter is not fully supported by TorchCodec AudioEncoder.

return save_with_torchcodec(   
/usr/local/lib/python3.12/dist-packages/torchaudio/__init__.py:178:
UserWarning: The 'bits_per_sample' parameter is not directly supported by TorchCodec AudioEncoder.
return save_with_torchcodec(
```
### README
Refer to the original repository for the README: https://github.com/adefossez/demucs
