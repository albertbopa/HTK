# HTK

Pagines tutorials auxiliars:

http://www.speech.kth.se/~matsb/speech_rec_course_2003/htk_tutorial.pdf
http://www1.icsi.berkeley.edu/Speech/docs/HTKBook/node22.html
http://www.ee.columbia.edu/~dpwe/LabROSA/doc/HTKBook21/node90.html
http://www.voxforge.org/home/dev/acousticmodels/linux/create/htkjulius/tutorial/monophones/step-6

Llistes d'errors HTK:

https://anggarrgoon.wordpress.com/2017/12/01/htk-error-list/

Comandes utilitzades:

HCompV 

    HCompV -C config -f 0.01 -m -S train_list.txt -M hmm0 Hmm_prototype

Comandes en procés:

HERest

    HERest -C config -I songs.mlf -t 250.0 150.0 1000.0 -S train_list.txt -H hmm0/macros -H hmm0/hmmdefs -M hmm1 labels0
