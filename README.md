function Baby() {
  this.name = 'name my baby';
  this.dueData = '2019-01-13';
  this.birthday = 'countdown';
}

Baby.prototype.isReady = function() {
  console.log('matron');
  console.log(`baby's name`);
}

Baby.prototype.countdown = function() {
  console.log('countdown');
  this.birth();
}

Baby.prototype.birth = function() {
  console.log('baby birth');
}

const baby = new Baby();

baby.countdown();
