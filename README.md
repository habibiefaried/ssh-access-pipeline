# ssh-access-pipeline
SSH Access Pipeline demo with ansible

# Cara pakai

1. Pull request
2. Tambahkan user di `all.yaml`
3. Tambahkan public key di folder `files` dengan format `<username>.pub`
4. Apabila disetujui dan pengecekan berhasil, maka merge
5. Tunggu sampai job selesai di `master` branch

# Reference

https://minimum-viable-automation.com/ansible/use-ansible-create-user-accounts-setup-ssh-keys