<template>
    <Headline></Headline>
    <Search></Search>
    <MovieList></MovieList>
</template>

<script>
import Headline from '../components/Headline';
import MovieList from '../components/MovieList';
import Search from '../components/Search';

export default{
    components:{
    Headline,
    Search,
    MovieList
}
}
</script>