# style
from MyQR import myqr
import os
words = "http://47.102.201.63:9999/"
version, level, qr_name = myqr.run(
    words = words,
    version=1,
    level='H',
    picture="520.jpg",
    colorized=True,
    contrast=1.0,
    brightness=1.0,
    save_name=None,
    save_dir=os.getcwd()
)
