from indicators import get_rsi_signal

def run():
    signal = get_rsi_signal("BTC/USDT")
    if signal:
        print("Signal:", signal)

if __name__ == "__main__":
    run() import numpy as np

def get_rsi_signal(symbol):
    # dummy RSI logic
    rsi = 30
    if rsi < 30:
        return "BUY"
    if rsi > 70:
        return "SELL"
    return None
