Android TOAST
================

## Desarrollo

```Java
Context context = getApplicationContext();
CharSequence text = "Hello toast!";
int duration = Toast.LENGTH_SHORT;

Toast toast = Toast.makeText(context, text, duration);
toast.show();
```

## Fuente

* <a href="https://developer.android.com/guide/topics/ui/notifiers/toasts.html">Toasts</a>
* <a href="https://stackoverflow.com/questions/3500197/how-to-display-toast-in-android">How to display Toast in Android?</a>