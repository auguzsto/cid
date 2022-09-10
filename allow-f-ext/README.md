# Exemplificação.
No diretório Models terá alguns modelos(.txt) de vetos files, como por exemplo "Permitir Imagens e Compactados" ou "Permitir Imagens". Exemplo: No modelo "Permitir Imagens e Compactados", como próprio nome já diz, permite a exceção de extensões .PNG, .JPG, .BMP, .RAR, .ZIP. 

# Padrão do veto files.
Por padrão, em functions, o veto file está com extensões com assoativa à executáveis, macros, imagens, compactados, bat, etc.

# Como adicionar exceções.
No diretório allow-f-ext, abra o arquivo smb.conf e faça a adiação manualmente. 

Exemplo:
    [exemplo] ##LIBERADO ARQ. PNG, JPG, BMP DO COMPARTILHADO "EXEMPLO".
	veto files = /*.bat/*.cmd/*.nds/*.pif/*.com/*.scr/*.exe/*.dll/*.msp/*.msi/*.msu/*.ini/*.inf/*.jad/*.jar/*.reg/*.vbs/*.dat/*.cab/*.html/*.php/*.ps1/*.scr/*.ws/*.GADGET/*.msp/*.com/*.cpl/*.msc/*.etc/*.vbe/*.js/*.se/*.wsf/*.wsc/*.ps2/*.ps2xml/*.psc1/*.psc2/*.msh/*.msh1/*.msh1xml/*.mshxml/*.scf/*.inf/*.DOCM/*.DOTM/*.XLSM/*.XLTM/*.XLAM/*.PPTM/*.POTM/*.PPAM/*.PPSM/*.SLDM/*.mp3/*.mp4/*.mkv/*.webp/*.xdvi/*.gz/*.ARC/*.arj/*.bin/*dmg/*.gzip/*.hqx/*.sit/*.sitx/*.se/*.ace/*.uu/*.uue

# Copie e cole esse modelo no arquivo smb.conf e reinicie o serviço.
