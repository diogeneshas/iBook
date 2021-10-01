<template>
    <div class="presentation">
        <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Suscipit, iste officiis quam iusto eos maxime expedita eaque neque
             atque tenetur delectus nostrum inventore sapiente vitae natus tempora optio nobis doloremque esse magni a, modi at? Dicta 
             voluptatibus obcaecati repudiandae numquam corrupti asperiores sunt provident fugiat? Maiores obcaecati omnis mollitia corrupti!
        </p>

        <img src="@/assets/img/presentation.svg" alt="Apresentacao do iBook">
    </div>
</template>


<style lang="scss" scoped>

.presentation {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 2rem;
  align-items: center;
  @include screen('small', 'medium') {
    grid-template-columns: 1fr;
  }
  p {
    line-height: 26px;
  }
  img {
    max-width: 100%;
  }
}

</style>