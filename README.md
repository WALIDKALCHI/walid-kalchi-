# walid-kalchi-function displayMessage() {
    const mood = document.getElementById('moodSelector').value;
    const message = document.getElementById('message');

    if (mood === 'happy') {
        message.textContent = 'Great to hear that you are feeling happy!';
        message.style.color = 'green';
    } else if (mood === 'sad') {
        message.textContent = 'Sorry to hear that you are feeling sad. Things will get better!';
        message.style.color = 'blue';
    } else if (mood === 'angry') {
        message.textContent = 'Take a deep breath. Anger is natural, but don\'t let it control you!';
        message.style.color = 'red';
    } else {
        message.textContent = 'Stay positive! It\'s okay to have neutral days too.';
        message.style.color = 'gray';
    }
}
