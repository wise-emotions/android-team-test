<p align="center">
<img src="TelepassDigital.png" alt="Telepass digital logo" width="350">
</p>

# Telepass digital Android Test

Develop an app that shows a Pokémon list with its image and name.
When a user taps on a Pokémon, the app will show a detailed view of Pokémon’s name, images, stats, and category (fire, smoke, etc).

The APIs are available at the [following address](https://pokeapi.co).

## Guidelines

1. Use [Kotlin](https://kotlinlang.org/) based, [Coroutines](https://github.com/Kotlin/kotlinx.coroutines) + [Flow](https://kotlin.github.io/kotlinx.coroutines/kotlinx-coroutines-core/kotlinx.coroutines.flow/) for asynchronous. 
2. Minimum SDK level 23.
3. Use Clean Architecture (Repository pattern).
4. Use the MVI pattern ([Uniflow] (https://github.com/uniflow-kt/uniflow-kt)).
5. Use [Koin] (https://github.com/InsertKoinIO/koin) or [Hilt](https://dagger.dev/hilt/) for dependency injection.
6. Use [Retrofit2 & OkHttp3](https://github.com/square/retrofit) - construct the REST APIs and paging network data.
7. Use [Moshi](https://github.com/square/moshi/).
8. Use [Glide](https://github.com/bumptech/glide), [GlidePalette](https://github.com/florent37/GlidePalette) - loading images.
9. Create a `README.md` file where you describe the project and your choices.
10. Put your project on a public repository on [GitHub](https://github.com/).

## Bonus Tasks

1. Use one external library at most
2. Make the app work seamlessly also offline
3. Write Unit Tests
4. Personalize the project with something that may be useful to this app