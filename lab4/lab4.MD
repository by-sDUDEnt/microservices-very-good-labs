1. Два круд сервіси, на кожен окрема бд
2. Міграції написані на ноді, за допомоги pg-migrate. БД - пострес
3. Фронт працює з беком через інгрес (не найкращий варіант), тому в мене є підозра
що на лінуксі піднятий кластер не працюватиме, бо шляхи прописані на localhost, а не minikube ip.

Відомо, що це неправильно, але сподіваюся що на 2 лабу це зійде, потім виправимо.

