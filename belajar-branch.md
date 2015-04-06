# Belajar branch

## Membuat branch

* Command : `git branch <nama-branch>`
* Contoh : `git branch fix125`


## Pindah branch

* Command : `git checkout <nama-branch>`
* Contoh : `git checkout fix125`

## Ambil commit dari upstream

* Command : git fetch <nama-upstream>

## Merge commit dari upstream ke master di local

1. Pindah dulu ke master

    ```git checkout master```

2. Fetch upstream

    ```git fetch upstream```

3. Merge upstream ke master lokal

    ```git merge upstream/master```