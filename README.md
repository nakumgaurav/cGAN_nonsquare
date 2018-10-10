Train:
python myPix2Pix.py --mode train --output_dir ds/train/ --max_steps 1000

Test:
python myPix2Pix.py --mode test --input_dir ds/test/ --output_dir ds/output_imgs/ --checkpoint
