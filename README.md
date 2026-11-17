# BirthdayWebsite
<div class="birthday-photo">
    <img src="https://images.unsplash.com/photo-1530103862676-de8c9debad1d?w=1000"
         alt="Birthday Celebration">
</div>

<style>
.birthday-photo {
    width: 90%;
    max-width: 650px;
    margin: 25px auto;
    border-radius: 20px;
    overflow: hidden;
    box-shadow: 0 10px 35px rgba(255, 80, 170, 0.4);
}

.birthday-photo img {
    width: 100%;
    height: 320px;
    object-fit: cover;
    display: block;
    border-radius: 20px;
    transition: transform 0.5s ease;
}

.birthday-photo img:hover {
    transform: scale(1.05);
}
</style>
