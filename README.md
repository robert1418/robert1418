/* From Uiverse.io by andrew-demchenk0 */ 
.card {
  --main-color: #000;
  --bg-color: #EBD18D;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  width: 300px;
  padding: 25px;
  background: var(--bg-color);
  border-radius: 20px;
}

.card__wrapper {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
}

.card___wrapper-acounts {
  position: relative;
  display: flex;
  flex-direction: row;
  align-items: center;
  z-index: 1;
  cursor: pointer;
}

.card___wrapper-acounts > div:nth-child(2) {
  position: absolute;
  left: 25px;
  z-index: -1;
}

.card___wrapper-acounts > div:nth-child(3) {
  position: absolute;
  left: 50px;
  z-index: -2;
}

.card__score {
  display: flex;
  justify-content: center;
  align-items: center;
  font-weight: 500;
  font-size: 16px;
  color: #fff;
  width: 40px;
  height: 40px;
  border-radius: 100%;
  background: var(--main-color);
}

.card__acounts {
  width: 42px;
  height: 42px;
}

.card__acounts svg {
  width: 100%;
  height: 100%;
}

.card__menu {
  width: 40px;
  height: 40px;
  background: #F6DB96;
  border-radius: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
}

.card__title {
  margin-top: 50px;
  font-weight: 900;
  font-size: 25px;
  color: var(--main-color);
}

.card__subtitle {
  margin-top: 15px;
  font-weight: 400;
  font-size: 15px;
  color: var(--main-color);
}

.card__indicator {
  margin-top: 50px;
  font-weight: 500;
  font-size: 14px;
  color: var(--main-color);
}

.card__progress progress {
  width: 100%;
  height: 4px;
  border-radius: 100px;
}

.card__progress progress::-webkit-progress-bar {
  background-color: #00000030;
  border-radius: 100px;
}

.card__progress progress::-webkit-progress-value {
  background-color: var(--main-color);
  border-radius: 100px;
}


