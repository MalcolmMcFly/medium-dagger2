# Dagger 2

[![Build Status](https://travis-ci.org/MrBean355/medium-dagger2.svg?branch=master)](https://travis-ci.org/MrBean355/medium-dagger2)

This repository contains the sample code from my [Medium article](https://medium.com/dvt-engineering/android-dagger-2-isnt-hard-97671ac15b07) titled "Android: Dagger 2 Isn't Hard". Check it out for a walk-through of the project.

**Activity:** contains a RecyclerView to display Pokémon dictated by its view model

**View model:** fetches Pokémon from the repository

**Repository:** fetches Pokémon from the service once and stores them in the cache for subsequent calls

**Service:** makes a service call to fetch Pokémon

**Cache:** stores some Pokémon in memory

# Dagger

**@Inject** fields: tell Dagger to set these fields for us

**@Inject** constructors: tell Dagger to use this constructor when trying to instantiate the class

**@Provides** & @Binds methods: tell Dagger how to satisfy our dependencies

**@Module** classes: contain the various @Provides & @Binds methods

**@Component** class: binds all @Module classes into a dependency graph
