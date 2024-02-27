Логи

1

override fun onCreate(savedInstanceState: Bundle?) {
    super.onCreate(savedInstanceState)
    Log.d(TAG, "onCreate: Activity created")

    setContent {
        //...
    }
}

Результат: Логирование добавлено в метод onCreate. Когда активность создается, будет выведено сообщение "Activity created" в консоль логов.

2

override fun onStart() {
    super.onStart()
    Log.d(TAG, "onStart: Activity started")
}

Результат: Логирование добавлено в метод onStart. Когда активность стартует, будет выведено сообщение "Activity started" в консоль логов.

3

override fun onResume() {
    super.onResume()
    Log.d(TAG, "onResume: Activity resumed")
}

Результат: Логирование добавлено в метод onResume. Когда активность возобновляется, будет выведено сообщение "Activity resumed" в консоль логов.

4

override fun onPause() {
        super.onPause()
        Log.d(TAG, "onPause: Activity paused")
    }

Результат: Логирование добавлено в метод onPause. Когда активность на паузе, будет выведено сообщение "Activity paused" в консоль логов.

5

override fun onStop() {
        super.onStop()
        Log.d(TAG, "onStop: Activity stopped")
    }

Результат: Логирование добавлено в метод onStop. Когда активность останавливается, будет выведено сообщение "Activity stopped" в консоль логов.

6

override fun onDestroy() {
        super.onDestroy()
        Log.d(TAG, "onDestroy: Activity destroyed")
    }

Результат: Логирование добавлено в метод onDestroy. Когда активность уничтожается, будет выведено сообщение "Activity destroyed" в консоль логов.

7

override fun onConfigurationChanged(newConfig: android.content.res.Configuration) {
    super.onConfigurationChanged(newConfig)
    Log.d(TAG, "onConfigurationChanged: Configuration changed")
}

Результат: Логирование добавлено в метод onConfigurationChanged. Когда происходит изменение конфигурации, например, поворот экрана, будет выведено сообщение "Configuration changed" в консоль логов.
