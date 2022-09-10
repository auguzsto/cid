# Exemplificação.
No diretório Models terá alguns modelos(.txt) de vetos files, como por exemplo "Permitir Imagens e Compactados" ou "Permitir Imagens". Exemplo: No modelo "Permitir Imagens e Compactados", como próprio nome já diz, permite a exceção de extensões .PNG, .JPG, .BMP, .RAR, .ZIP. 

# Padrão do veto files.
Por padrão, em functions, o veto file está com extensões com assoativa à executáveis, macros, imagens, compactados, bat, etc.

# Como adicionar exceções.
No diretório allow-f-ext, abra o arquivo smb.conf e faça a adiação manualmente. 

Exemplo:

![image](https://user-images.githubusercontent.com/40308971/189494892-fd26920c-4c1b-414b-a900-99e38f2caf9f.png)

# Copie e cole esse modelo no arquivo smb.conf e reinicie o serviço.
