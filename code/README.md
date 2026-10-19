# Inter IIT Tech Meet 15.0 Selection Bootcamp

Run all the cells of `iteration1.ipynb`. It will generate all the required files in the specified format.


The seed written in the results.json is what was recovered from `torch.initial_seed()` after the whole run from the same kernel.
I am getting `INVALID: header must be 'epoch,train_acc_correct,train_acc_mislabeled,val_acc_noisy,val_acc_clean'` in `t2_dynamics.csv` when testing using `python check_format.py ..` even though the names are exactly the same.